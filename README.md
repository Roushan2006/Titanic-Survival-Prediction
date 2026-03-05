# 🚢 Titanic Survival Prediction

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)

Predict whether a passenger survived the Titanic disaster using **Machine Learning classification models**.

---

## 📌 Project Overview

This project uses the **Titanic dataset** to build ML models that predict passenger survival.

Steps performed in this project:

* Data Cleaning
* Feature Encoding
* Train/Test Split
* Model Training
* Model Evaluation

---

## 📊 Models Used

The following models were trained:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Gaussian Naive Bayes
* Decision Tree Classifier

---

## 📂 Dataset

Dataset loaded using:

```python
import seaborn as sns
df = sns.load_dataset("titanic")
```

Important features:

* Age
* Sex
* Passenger Class
* Fare
* Siblings/Spouses
* Embarked Port

---

## ⚙️ Data Preprocessing

Steps performed:

* Removed unnecessary columns
* Handled missing values
* Encoded categorical variables
* Converted boolean values

---

## 🔀 Train Test Split

```python
train_test_split(test_size=0.2, random_state=42)
```

* 80% Training Data
* 20% Testing Data

---

## 📈 Model Evaluation

Evaluation metrics used:

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## 📦 Libraries Used

* pandas
* seaborn
* scikit-learn

Install requirements:

```bash
pip install pandas seaborn scikit-learn
```

---

## ▶️ How to Run

Clone the repository

```bash
git clone https://github.com/yourusername/titanic-ml-project.git
```

Open the notebook

```bash
jupyter notebook simple.ipynb
```

---

## 👨‍💻 Author

**Roushan Kumar**

