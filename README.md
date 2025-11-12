<h1 align="center">📊 Student Performance Analysis — End-to-End Data Science & Machine Learning Project</h1>
<h3 align="center">EDA • Feature Engineering • ML Model • Insights Visualization</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=black"/>
  <img src="https://img.shields.io/badge/Random_Forest-228B22?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
</p>

---

## 🧠 Project Summary

The goal of this project is to analyze factors affecting student academic performance and build a Machine Learning model that predicts their **performance level (Low / Medium / High)** using subjects like Math, Reading & Writing.

✅ Real education dataset (1000 students)  
✅ Detailed Exploratory Data Analysis  
✅ Feature engineering + ML model + visual insights  
✅ Auto-generated charts stored in `/visuals/`

---

## 📂 Repository Structure

📦 Student Performance Analysis
│
├── 📄 StudentsPerformance.csv → Dataset used
├── 📓 Student Performance Data Analysis.ipynb → Full EDA + ML Notebook
└── 📊 visuals/ → All generated visualizations

yaml
Copy code

---

## 📊 Data Science Workflow

```mermaid
flowchart TD
    A[Load Dataset] --> B[Clean & Preprocess Data]
    B --> C[EDA (Visualization & Insights)]
    C --> D[Feature Engineering]
    D --> E[Train Random Forest Classifier]
    E --> F[Model Evaluation & Accuracy]
🧩 Feature Engineering
New Feature	Why it was created
average_score	Captures combined performance across subjects
performance_level	Converts marks into ML class labels (Low / Medium / High)

python
Copy code
df["average_score"] = (df.math_score + df.reading_score + df.writing_score) / 3
🔍 Key Visual Insights
✅ Students who completed test preparation scored higher
✅ Better parental education → higher probability of good performance
✅ Reading & Writing scores are strongly correlated
✅ Standard lunch students score better than reduced lunch

mermaid
Copy code
graph LR
Math --> Reading
Reading --> Writing
Math --> Writing
🤖 Machine Learning Model
Parameter	Value
Model	RandomForestClassifier
Target Variable	performance_level
Achieved Accuracy	~89%

Model training:

python
Copy code
model = RandomForestClassifier()
model.fit(X_train, y_train)
pred = model.predict(X_test)
🔧 Tech Stack Used
Category	Tools
Languages	Python
Libraries	Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
Platform	Jupyter Notebook / Google Colab

▶️ Run This Project Locally
Clone this repository

Install dependencies

bash
Copy code
pip install pandas numpy seaborn matplotlib scikit-learn
Open notebook

bash
Copy code
jupyter notebook
Run Student Performance Data Analysis.ipynb

📈 Outputs Saved Automatically
📁 /visuals/ folder contains:

Histogram distributions

Correlation heatmap

Boxplots (gender & parental education)

Confusion matrix (ML results)

✅ Conclusion
This project demonstrates:

How student performance is influenced by external factors

How ML can classify performance categories

End-to-end DS pipeline from EDA → Feature Engineering → Classification Model

Data isn’t just numbers — it reveals patterns, decisions, and stories.

✨ Author
Sujal Singh
Data Science • Machine Learning • AI Projects

<p align="center"> <a href="https://github.com/sujal128"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a> <a href="https://www.linkedin.com/in/sujal-singh-40657728b/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a> </p> <p align="center"><b>“Data transforms assumptions into insights.”</b></p> ```
