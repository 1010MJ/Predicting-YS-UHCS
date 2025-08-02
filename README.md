# 🔩 Steel Yield Strength Prediction

A machine learning project focused on predicting the **Yield Strength (YS)** of Ultra-High Carbon Steels (UHCS) using their compositional and thermal processing parameters.
This can support materials scientists in designing alloys with tailored mechanical properties.

---

## 🧠 Overview

In metallurgical engineering, **predicting mechanical properties** like Yield Strength from processing parameters and composition is a challenging yet critical task. 
This project leverages machine learning to create a predictive model for YS, using data provided by IIT on steel samples. 
The goal is to assist materials development with fast, accurate computational predictions.

---
## 🧩 Problem Addressed

The project aims to predict the **Yield Strength (YS)** of Ultra-High Carbon Steels using machine learning, based on their chemical composition and heat treatment parameters. In materials science, traditional testing is time-consuming and expensive. This model provides a fast, data-driven alternative by learning patterns from existing experimental data.

## ✅ Solution Approach

A complete machine learning pipeline was developed to address these challenges:

- Performed data cleaning, transformation, and feature selection.
- Applied regression models including Linear Regression, Random Forest, and XGBoost.
- Evaluated models using metrics like RMSE and R².
- Interpreted feature importance to understand drivers of yield strength.

This solution enables faster, cost-efficient yield strength estimation and supports materials design

## ❗ Challenges Addressed

- 🔬 Non-linear relationship between input parameters and YS.
- 📉 Limited and imbalanced dataset.
- 📊 Feature selection from metallurgical data (e.g., Mn, C%, cooling rate).
- ⚖️ Model generalization across a wide range of thermal processes.

---

## 📂 Dataset Information

- **Source**: Internal dataset from Indian Institute of Technology (IIT).
- **Format**: `.xlsx` or `.csv` used after cleaning and preprocessing.
- **Size**: ~200-500 samples of steels with columns like:
  - Chemical compositions (C, Mn, Si, etc.)
  - Heat treatment parameters (Austenitization temp, Quenching temp)
  - Mechanical properties (YS in MPa)

> Note: Data is not publicly released due to confidentiality. Placeholder or synthetic data can be used for demonstration.

---

## ⚙️ Technologies Used

| Tool / Library    | Purpose                          |
|------------------|----------------------------------|
| Python (3.x)      | Core programming language         |
| NumPy & Pandas    | Data wrangling                    |
| Matplotlib & Seaborn | Exploratory data analysis and visualization |
| Scikit-learn      | ML models (Linear, Ensemble)      |
| XGBoost / LightGBM| Advanced regression modeling      |
| Jupyter Notebook  | Interactive development           |

---

## 🔁 Project Workflow


A[Load Dataset] --> B[Data Cleaning]
B --> C[Exploratory Data Analysis]
C --> D[Feature Engineering]
D --> E[Train-Test Split]
E --> F[Model Training]
F --> G[Hyperparameter Tuning]
G --> H[Model Evaluation]
H --> I[Export/Save Model]
