# 🩺 Breast Cancer Classification using Machine Learning

A Machine Learning classification project that predicts whether a breast tumor is **Malignant** or **Benign** using the **Breast Cancer Wisconsin Dataset** from scikit-learn. The project demonstrates the complete machine learning workflow, including data preprocessing, model training, evaluation, ROC-AUC analysis, handling class imbalance, and model comparison.

---

## 📌 Project Overview

This project focuses on implementing and evaluating binary classification models for breast cancer diagnosis. The primary model used is **Logistic Regression**, which is compared with a **Decision Tree Classifier** to analyze performance differences.

The project covers essential machine learning concepts such as:

* Data preprocessing
* Feature scaling
* Binary classification
* Model evaluation
* Confusion Matrix
* Precision, Recall, and F1-Score
* ROC Curve & AUC Score
* Handling imbalanced datasets
* Model comparison

---

## 🎯 Objectives

* Build a binary classification model using Logistic Regression.
* Predict whether a tumor is malignant or benign.
* Evaluate model performance using multiple metrics.
* Handle class imbalance using class weights.
* Compare Logistic Regression with Decision Tree Classifier.
* Understand the importance of evaluation metrics beyond accuracy.

---

## 📂 Dataset

**Dataset:** Breast Cancer Wisconsin Dataset

* Source: `sklearn.datasets.load_breast_cancer()`
* Number of Samples: **569**
* Number of Features: **30**
* Target Classes:

  * Benign
  * Malignant

The dataset is included within the scikit-learn library, so no external download is required.

---

## 🛠️ Technologies Used

* Python 3.x
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 📚 Machine Learning Concepts Covered

* Supervised Learning
* Binary Classification
* Logistic Regression
* Decision Tree Classification
* Train-Test Split
* Feature Scaling
* Standardization
* Confusion Matrix
* Precision
* Recall
* F1-Score
* ROC Curve
* AUC Score
* Handling Imbalanced Data
* Model Comparison

---

## 📁 Project Structure

```text
Breast-Cancer-Classification/
│
├── Breast_Cancer_Classification.ipynb
├── README.md
├── requirements.txt
└── screenshots/
    ├── confusion_matrix.png
    ├── roc_curve.png
    └── model_comparison.png
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Breast-Cancer-Classification.git
```

Navigate to the project directory:

```bash
cd Breast-Cancer-Classification
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

## 📊 Workflow

1. Import required libraries
2. Load the Breast Cancer dataset
3. Explore and inspect the data
4. Split data into training and testing sets
5. Standardize numerical features
6. Train Logistic Regression model
7. Generate predictions
8. Evaluate using:

   * Confusion Matrix
   * Classification Report
   * ROC Curve
   * AUC Score
9. Handle class imbalance using `class_weight='balanced'`
10. Train Decision Tree Classifier
11. Compare both models

---

## 📈 Evaluation Metrics

The project evaluates model performance using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC Curve
* AUC Score

These metrics provide a complete understanding of classification performance rather than relying solely on accuracy.

---

## 📷 Results

The notebook generates:

* Dataset overview
* Class distribution
* Confusion Matrix
* Classification Report
* ROC Curve
* AUC Score
* Balanced Logistic Regression results
* Decision Tree performance
* Model comparison table

---

## 🎓 Learning Outcomes

After completing this project, you will understand:

* How binary classification works
* Logistic Regression implementation
* Decision Tree Classification
* Data preprocessing techniques
* Feature scaling
* Classification metrics
* ROC-AUC analysis
* Handling imbalanced datasets
* Comparing machine learning models

---

## 🔮 Future Improvements

* Hyperparameter tuning using GridSearchCV
* Cross-validation for improved evaluation
* Random Forest Classifier
* Support Vector Machine (SVM)
* XGBoost Classifier
* Feature selection techniques
* Model deployment using Flask or Streamlit
* Interactive web application for predictions

---

## 📦 Requirements

```text
numpy
pandas
matplotlib
scikit-learn
jupyter
```

Install them using:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is intended for educational and learning purposes.

---

## 👨‍💻 Author

**Rudra Dahikar**

Machine Learning | Data Science | Python Developer

GitHub: https://github.com/your-username

LinkedIn: https://linkedin.com/in/your-profile
