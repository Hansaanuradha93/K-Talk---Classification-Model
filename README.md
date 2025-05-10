# 🧠 Leptospirosis Prediction using Machine Learning

This repository contains a complete machine learning workflow to analyze, preprocess, and model a medical dataset for **Leptospirosis diagnosis**. It demonstrates how data cleaning, feature engineering, and model selection impact classification accuracy. The entire process is presented using **Jupyter Notebooks** with interactive visualizations and performance evaluation.

---

## 📂 Project Structure

├── Model_Trains.ipynb # Main notebook: Data cleaning, training, evaluation
├── requirements.txt # Python dependencies
├── .gitignore # Ignore files/folders (MacOS + Python)
└── README.md # Project documentation (this file)

---

## 📊 Workflow Overview

### 1. Data Understanding & Exploration

- Dataset shape and structure inspection
- Visualization of target distribution
- Summary statistics and missing value analysis

### 2. Data Preprocessing

- Handling missing values
- Feature selection and encoding
- Train-test split using stratified sampling

### 3. Feature Engineering

- Transforming categorical variables
- Creating new features (if necessary)
- Normalization or scaling (where required)

### 4. Model Training

We trained and evaluated several classification models:

- ✅ Random Forest
- ✅ Gradient Boosting
- ✅ Logistic Regression
- ✅ Support Vector Machine (SVM)
- ✅ K-Nearest Neighbors (KNN)
- ✅ Naive Bayes

### 5. Evaluation Metrics

Each model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score

Evaluation results are visualized using grouped bar plots and separate metric-wise comparison plots.

---

## 📈 Visualization Samples

- Target class distribution
- Missing data heatmaps
- Bar charts comparing model performance metrics

---

## 🚀 How to Run This Project

### 1. Clone the Repository

````bash
git clone https://github.com/yourusername/leptospirosis-ml.git
cd leptospirosis-ml

### 2. Create a Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate  # For Mac/Linux

### 3. Install Dependencies

```bash
pip install -r requirements.txt

### 4. Install Dependencies

```bash
jupyter notebook

## 📌 Requirements

- Python 3.8 or later
- Jupyter Notebook
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- xgboost

You can install all required packages using:

```bash
pip install -r requirements.txt

## ✍️ Author

**Hansa Wickramanayake**
📧 [hansaanuradha93@gmail.com]
🐙 [GitHub](https://github.com/Hansaanuradha93)
````
