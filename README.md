# 🩺 Diabetes Prediction using Machine Learning

This project is a **machine learning–based classification system** that predicts whether a person is **diabetic or non-diabetic** based on medical diagnostic data.
It uses a **Support Vector Machine (SVM)** classifier with proper **data standardization**, following a complete and correct ML pipeline.

The project showcases strong fundamentals in **data preprocessing, feature scaling, model training, and evaluation**.

---

## 📌 Problem Statement

Diabetes is a chronic medical condition that can be detected early using diagnostic measurements such as glucose level, BMI, insulin, age, and more.

The goal of this project is to build a model that can accurately predict:

* **0 → Non-Diabetic**
* **1 → Diabetic**

based on patient health parameters.

---

## 🚀 Key Features

* Loads and analyzes real-world medical dataset
* Performs statistical analysis and class distribution checks
* Applies **feature standardization** using `StandardScaler`
* Trains a **Support Vector Machine (SVM)** classifier
* Evaluates accuracy on training and test datasets
* Predicts diabetes status for new patient input data

---

## 🧠 Machine Learning Workflow

### 1️⃣ Data Collection & Analysis

* Diabetes dataset loaded into a Pandas DataFrame
* Exploratory analysis using:

  * `.head()`
  * `.describe()`
  * Outcome distribution

### 2️⃣ Data Preprocessing

* Separation of features and target labels
* Feature scaling using **StandardScaler**
* Ensures all features contribute equally to the model

### 3️⃣ Train-Test Split

* 80% training data
* 20% testing data
* Stratified split to preserve class balance

### 4️⃣ Model Training

* **Support Vector Machine (SVM)** with linear kernel
* Trained on standardized medical features

### 5️⃣ Model Evaluation

* Accuracy score on:

  * Training data
  * Test data

### 6️⃣ Predictive System

* Accepts new patient data
* Standardizes input
* Predicts diabetic or non-diabetic outcome

---

## 🛠 Tech Stack Used

### Programming Language

* **Python 3**

### Libraries & Frameworks

* **NumPy** – Numerical operations
* **Pandas** – Data handling and analysis
* **Scikit-learn**

  * `StandardScaler`
  * `train_test_split`
  * `svm.SVC`
  * `accuracy_score`

### Tools

* Google Colab / Jupyter Notebook
* Git & GitHub

---

## 📊 Model Performance

* **Training Accuracy**: High accuracy indicating good learning
* **Test Accuracy**: Competitive accuracy showing effective generalization

*(Exact values may vary depending on random state and data split)*

---

## ▶️ How to Run the Project

### 1️⃣ Install Required Libraries

```bash
pip install numpy pandas scikit-learn
```

### 2️⃣ Run the Script

```bash
python diabetes_prediction.py
```

---

## 🧪 Example Prediction

```text
Input: Patient health parameters (e.g., glucose, BMI, age)
Output:
- The person is Diabetic
- The person is not Diabetic
```

---

## 📁 Dataset Information

* **Features** include:

  * Pregnancies
  * Glucose
  * Blood Pressure
  * Skin Thickness
  * Insulin
  * BMI
  * Diabetes Pedigree Function
  * Age
* **Target Variable**: `Outcome`

  * `0` → Non-Diabetic
  * `1` → Diabetic

---

## 💡 Why Recruiters Care About This Project

* Demonstrates **real-world healthcare ML application**
* Uses proper **data standardization** (often missed by beginners)
* Implements **SVM**, a core ML algorithm
* Covers the **complete ML lifecycle**
* Clean, readable, and logically structured code

This project clearly shows your understanding of **applied machine learning**, not just theory.

---

## 🔮 Future Enhancements

* Add confusion matrix & classification report
* Experiment with different kernels (RBF, Polynomial)
* Hyperparameter tuning using GridSearchCV
* Build a web app using Flask / FastAPI
* Deploy the model for real-time predictions

---

## 👨‍💻 Author

**Diganta Ghosh**
B.Tech – Computer Science Engineering (AI)
Aspiring Machine Learning & AI Engineer

---
