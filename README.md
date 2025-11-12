<h1 align="center">📊 Student Performance Analysis — End-to-End Data Science & Machine Learning Project</h1>
<h3 align="center">EDA • Feature Engineering • ML Model • Insights Visualization</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=black"/>
  <img src="https://img.shields.io/badge/Random_Forest-228B22?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
</p>

---

## 🧠 Project Summary

This project analyzes factors affecting student academic performance and builds a Machine Learning model that predicts **performance level (Low / Medium / High)** using scores from Math, Reading, and Writing.

✅ Real dataset (1000 students)  
✅ Detailed Exploratory Data Analysis  
✅ Feature engineering + ML model  
✅ Visual insights stored automatically in `/visuals/`

---

## 📂 Repository Structure

📦 Student Performance Analysis
│
├── 📄 StudentsPerformance.csv → Dataset
├── 📓 Student Performance Data Analysis.ipynb → Full EDA + ML Notebook
└── 📊 visuals/ → Saved visualization images

---

## 📊 Data Science Workflow

## 📊 Data Science Workflow


```mermaid
flowchart TD
    A[Load Dataset] --> B[Data Cleaning & Preprocessing]
    B --> C[Exploratory Data Analysis]
    C --> D[Feature Engineering]
    D --> E[Train Random Forest Model]
    E --> F[Evaluate Model Accuracy]
```


🧩 Feature Engineering
New Feature	Why it was created
average_score	Captures combined performance of all subjects
performance_level	Converts marks into ML class labels (Low / Medium / High)

df["average_score"] = (df.math_score + df.reading_score + df.writing_score) / 3

🔍 Key Visual Insights
✅ Students who completed test preparation scored higher
✅ Better parental education leads to better performance
✅ Reading & Writing have a strong correlation
✅ Students with standard lunch scored better

graph LR
Math --> Reading
Reading --> Writing
Math --> Writing

🤖 Machine Learning Model
Parameter	Value
Algorithm	RandomForestClassifier
Target	performance_level
Achieved Accuracy	~89%

model = RandomForestClassifier()
model.fit(X_train, y_train)
pred = model.predict(X_test)

🔧 Tech Stack Used
Category	Tools
Languages	Python
Libraries	Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
Platform	Jupyter Notebook / Google Colab

▶️ Run This Project Locally
Clone the repository

Install dependencies:
pip install pandas numpy seaborn matplotlib scikit-learn

Open notebook:
jupyter notebook

Run Student Performance Data Analysis.ipynb

📈 Outputs Saved Automatically
Folder /visuals/ contains:

Histograms

Correlation heatmap

Boxplots (based on gender/parent education)

Confusion matrix (ML model results)

✅ Conclusion
This project shows how:

Student performance is influenced by external & social factors

Machine Learning can categorize student performance levels

Complete DS pipeline from EDA → Feature Engineering → ML Classification

Data isn’t just numbers — it reveals patterns, decisions, and stories.

✨ Author
Sujal Singh
Data Science • Machine Learning • AI Projects

<p align="center"> <a href="https://github.com/sujal128"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a> <a href="https://www.linkedin.com/in/sujal-singh-40657728b/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a> </p> <p align="center"><b>“Data transforms assumptions into insights.”</b></p> ```
