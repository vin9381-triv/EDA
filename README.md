# Titanic Dataset – Exploratory Data Analysis (EDA)

This repository contains a **clean Jupyter notebook** where I explore the Titanic dataset step by step.  
The goal is **not modeling**, but to **practice and document the EDA process**: exploring distributions, spotting patterns, and handling missing values & outliers.

---

## 📂 Contents
- `EDA_github_ready.ipynb` → main EDA notebook (univariate, bivariate, multivariate analysis)
- `EDA_with_imputation_outlier.ipynb` → extended notebook with code for handling missing values and outliers
- `data/` → (not included; place Titanic CSVs here)
- `plots/` → auto-generated charts

---

## 🔍 What You’ll Learn
- How to systematically perform **univariate and bivariate analysis**
- How to explore **target vs features** (Survived vs Age, Fare, Pclass, etc.)
- How to check **feature-feature dependencies**
- How to handle **missing values** (Age, Fare, Embarked)
- How to handle **outliers** (Fare, Family size)

---

## 🚦 What This Repo Is *Not*
- It does **not** include modeling or prediction.  
- Instead, it focuses only on the **EDA decision-making process**.

👉 For a detailed write-up with explanations and reasoning (normalization, scaling, regularization, feature engineering), see the accompanying article:  
**[How to Decide Things in the EDA Process](https://your-article-link.com)**

---

## 🚀 How to Use
1. Clone/download the repo.  
2. Place Titanic CSVs into `data/`.  
3. Open either notebook in Jupyter or VS Code.  
4. Run cells to reproduce plots and results.  

---

## ✨ Next Steps
- Try feature engineering (FamilySize, Title extraction).  
- Compare group-based imputations vs simple imputations.  
- Extend this workflow into a full modeling pipeline.  
