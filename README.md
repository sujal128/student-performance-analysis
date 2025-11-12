<h1 align="center">📊 Student Performance Analysis — EDA + Machine Learning</h1>
<h4 align="center">End-to-End Data Science Pipeline | Classification Model | Insights + ML Explainability</h4>

---

## 📌 Objective

This project performs **Exploratory Data Analysis (EDA)** and builds a **Machine Learning classification model** to predict student performance levels (Low / Medium / High) using demographic & academic factors.

The workflow replicates a real industry DS pipeline:
> Data → Preprocessing → Feature Engineering → Visualization → Modeling → Evaluation

---

## 🧠 Problem Statement

> *“Can we predict a student’s academic performance level by examining factors such as gender, parental education, lunch type, and test preparation?”*

---

## ⚙️ End-to-End ML Pipeline

```text
┌─────────────────────────┐
│  Load Dataset (CSV)      │
└───────────────┬─────────┘
                ↓
┌─────────────────────────┐
│ Data Cleaning & Encoding │
│ (Label Encoding + Mapping) │
└───────────────┬─────────┘
                ↓
┌─────────────────────────┐
│ Feature Engineering      │
│ → average_score          │
│ → performance_level      │
└───────────────┬─────────┘
                ↓
┌─────────────────────────┐
│ Exploratory Data Analysis│
│ (Heatmap, Boxplots etc.) │
└───────────────┬─────────┘
                ↓
┌─────────────────────────┐
│ Model Training (RF)      │
└───────────────┬─────────┘
                ↓
┌─────────────────────────┐
│ Evaluation (Accuracy +   │
│ Confusion Matrix + FI)   │
└─────────────────────────┘
