# 🏠 Feature Engineering, Model Optimization & Performance Comparison

## 📌 Project Overview

This project focuses on predicting housing prices using the **California Housing Dataset**. The primary objective is to apply feature engineering, data preprocessing, and machine learning techniques to improve prediction accuracy and compare the performance of different regression models.

The project demonstrates a complete machine learning workflow, including data analysis, feature scaling, model training, evaluation, and performance comparison.

---

## 🎯 Objectives

* Analyze the California Housing Dataset.
* Perform data preprocessing and feature engineering.
* Apply feature scaling techniques.
* Train multiple regression models.
* Evaluate model performance using standard metrics.
* Compare models and identify the best-performing algorithm.

---

## 📂 Dataset

**Dataset:** California Housing Dataset

### Features

* Median Income
* Housing Median Age
* Average Rooms
* Average Bedrooms
* Population
* Average Occupancy
* Latitude
* Longitude

### Target Variable

* Median House Value

The dataset is available directly through Scikit-Learn.

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib

---

## ⚙️ Project Workflow

### 1. Data Loading

* Import California Housing Dataset.
* Convert dataset into a Pandas DataFrame.

### 2. Data Preprocessing

* Check for missing values.
* Explore dataset structure.
* Prepare data for model training.

### 3. Feature Engineering

* Select relevant features.
* Improve data quality and representation.

### 4. Feature Scaling

* Apply StandardScaler to normalize numerical features.

### 5. Model Training

The following machine learning models were implemented:

* Linear Regression
* Ridge Regression
* Decision Tree Regressor

### 6. Model Evaluation

Performance was evaluated using:

* RMSE (Root Mean Square Error)
* R² Score

### 7. Performance Comparison

Compare model results and identify the most accurate model.

---

## 📊 Results

| Model                   | RMSE | R² Score |
| ----------------------- | ---- | -------- |
| Linear Regression       | 0.7456 | 0.5758 |
| Ridge Regression        | 0.7456 | 0.5758 |
| Decision Tree Regressor | 0.7303 | 0.5930 |



---

## 📈 Visualizations

The project includes:

* Data Distribution Plots
* Correlation Analysis
* Actual vs Predicted Values Graph
* Model Performance Comparison Charts

---

## 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/housing-price-prediction.git
cd housing-price-prediction
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib scikit-learn
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and execute all cells.

---

## 📁 Project Structure

```text
├── data/
├── notebooks/
│   └── Housing_Price_Prediction.ipynb
├── images/
├── README.md
├── requirements.txt
└── report.pdf
```

---

## ✅ Key Learnings

* Data preprocessing techniques
* Feature engineering concepts
* Feature scaling using StandardScaler
* Regression model implementation
* Performance evaluation using RMSE and R²
* Comparative analysis of machine learning models

---

## 🔮 Future Improvements

* Hyperparameter tuning
* Random Forest Regressor
* XGBoost Regressor
* Cross-validation techniques
* Model deployment using Flask or Streamlit

---

## 📚 References

* Scikit-Learn Documentation
* Pandas Documentation
* NumPy Documentation
* Matplotlib Documentation
* California Housing Dataset Documentation

---

## 👨‍💻 Author

**Name:** Rudra Dahikar

Artificial Intelligence & Machine Learning Internship Project
