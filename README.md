# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

The Credit Card Fraud Detection System is a Machine Learning project developed to identify fraudulent credit card transactions. The project uses supervised learning algorithms to classify transactions as genuine or fraudulent by analyzing transaction patterns. It demonstrates a complete machine learning workflow, from data preprocessing to model evaluation and optimization.

---

## 🎯 Objectives

- Detect fraudulent credit card transactions.
- Compare multiple Machine Learning algorithms.
- Handle imbalanced datasets using SMOTE.
- Improve model performance through hyperparameter tuning.
- Build a reliable fraud detection model.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- imbalanced-learn (SMOTE)
- Joblib

---

## 📂 Dataset

The dataset contains anonymized credit card transactions with features required for fraud detection.

**Target Variable:**
- **0** → Genuine Transaction
- **1** → Fraudulent Transaction

---

## 📈 Machine Learning Workflow

- Data Loading
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Handling Imbalanced Data using SMOTE
- Feature Scaling
- Train-Test Split
- Model Training
- Hyperparameter Tuning using GridSearchCV
- Model Evaluation
- Saving the Best Model using Joblib

---

## 🤖 Machine Learning Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Since fraud detection requires minimizing missed fraudulent transactions, **Recall** was considered one of the most important evaluation metrics.

---

## ✨ Key Features

- Data Cleaning and Preprocessing
- SMOTE for Class Balancing
- Multiple Model Comparison
- Hyperparameter Optimization
- Model Serialization using Joblib
- End-to-End Machine Learning Pipeline

---


## 🚀 How to Run

1. Clone this repository.

```bash
git clone https://github.com/Shaikhaliya/credit-card-fraud-detection.git
```

2. Install the required libraries.

```bash
pip install pandas numpy matplotlib scikit-learn imbalanced-learn joblib
```

3. Open the Jupyter Notebook.

```bash
jupyter notebook
```

4. Run all cells to train and evaluate the models.

---

## 📌 Project Conclusion

The Credit Card Fraud Detection System was successfully developed using supervised machine learning techniques to identify fraudulent financial transactions. The project followed a complete machine learning pipeline, including data preprocessing, exploratory data analysis, handling class imbalance using **SMOTE**, model training, hyperparameter tuning with **GridSearchCV**, and model evaluation.

Multiple classification algorithms, including **Logistic Regression, Decision Tree, Random Forest, and K-Nearest Neighbors (KNN)**, were implemented and compared using **Accuracy, Precision, Recall, F1-Score, and Confusion Matrix**. Special emphasis was placed on **Recall**, as correctly identifying fraudulent transactions is critical in real-world fraud detection systems.

The final optimized model demonstrated strong predictive performance and was saved using **Joblib**, making it suitable for future deployment and real-time fraud detection applications.

This project enhanced practical knowledge in data preprocessing, handling imbalanced datasets, machine learning model development, performance evaluation, and predictive analytics. It also strengthened problem-solving, analytical thinking, and end-to-end machine learning implementation skills while addressing a real-world financial security challenge.

---

## 👩‍💻 Author

**Aliya Shaikh**

📧 Email: shaikhaliya2005@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/aliya-shaikh-297190397/

💻 GitHub: https://github.com/Shaikhaliya
