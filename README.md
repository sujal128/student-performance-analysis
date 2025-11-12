# 📊 Student Performance Analysis (EDA + Machine Learning)

A complete **Data Science & Machine Learning project** analyzing the Student Performance dataset.  
The goal is to explore factors affecting academic performance and build an ML model to **predict student performance levels**.

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `Student Performance Data Analysis.ipynb` | Full EDA + ML model + visualizations |
| `StudentsPerformance.csv` | Dataset used in the project |

---

## ✅ Key Highlights

✔ Loaded & Cleaned dataset  
✔ Feature Engineering (Created new feature: `average_score`)  
✔ Visualized relationships using **Seaborn & Matplotlib**  
✔ Built a **Random Forest Classifier** to predict performance levels  
✔ Saved publication-ready visuals

---

## 🔍 Insights from Data

- Female students performed slightly higher in reading & writing.
- Standard lunch students scored higher than those with reduced lunch.
- Completing test preparation course boosts scores significantly.
- Parental education influences performance trend.

---

## 🤖 Machine Learning Model

| Model Used | Random Forest Classifier |
|------------|--------------------------|
| Target | `performance_level` (Low / Medium / High) |
| Accuracy | **~89%** after rounding |

Key ML steps:
- Train/Test split
- Model training
- Evaluation using accuracy score

---

## 🛠️ Tech Stack

**Languages & Libraries**
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-Learn

---

## 📈 Visual Outputs Included

- Distribution of scores  
- Correlation heatmap  
- Performance level prediction result

All visuals are generated and stored automatically inside `/visuals/`.

---

## 🚀 How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
