
# ❤️ Heart Disease Prediction with Bayesian Network

![Python](https://img.shields.io/badge/Python-3.x-blue)
![AI](https://img.shields.io/badge/AI-Bayesian%20Networks-green)
![Dataset](https://img.shields.io/badge/Dataset-Kaggle-orange)
![Status](https://img.shields.io/badge/Academic%20Project-FAI%26KR-brightgreen)

---

## 📌 Project Overview

This project was developed for **Fundamentals of Artificial Intelligence & Knowledge Representation (FAI&KR) – Module 3**.

The objective of this project is to predict the probability of heart disease using **Bayesian Networks** implemented in Python.

Two different Bayesian Network approaches were implemented and compared:

* A manually designed Bayesian model
* A structure learned model using Hill Climbing

---

## 📊 Dataset

The dataset was obtained from the **Kaggle Heart Disease Dataset**.

It includes medical attributes such as:

* Age
* Sex
* Cholesterol
* Resting Blood Pressure
* Chest Pain Type
* Fasting Blood Sugar
* Maximum Heart Rate
* Other clinical indicators

These features were used to estimate the probability of heart disease in patients.

---

## 🧠 Methodology

### 🔹 Manual Bayesian Network

* Network structure designed based on medical reasoning.
* Dependencies between variables were defined manually.
* Conditional Probability Tables (CPTs) were computed from data.

### 🔹 Hill Climbing Learned Model

* Structure automatically learned from the dataset.
* Hill Climbing algorithm used for structure optimization.
* Model discovered relationships directly from data.

### 🔹 Probabilistic Inference

* Performed inference queries on both models.
* Calculated probabilities such as:

  * P(Heart Disease | Age, Sex, Cholesterol)
  * P(Heart Disease | High Cholesterol)

---

## 📈 Results

Both models confirmed that:

* **Age** is a major risk factor.
* **Sex** influences the probability of heart disease.
* **Cholesterol level** significantly increases risk.

The consistency between the manual and learned models strengthens the reliability of Bayesian Networks in medical prediction tasks.

---

## 📂 Project Structure

```
Heart-Disease-Prediction-With-Bayes-Net/
│
├── Heart_Disease_BayesNet.ipynb
├── Project_Report.pdf
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository

```
git clone <your-repository-link>
```

2. Install required libraries

```
pip install pandas numpy pgmpy matplotlib
```

3. Open the notebook

```
jupyter notebook
```

4. Run all cells to reproduce results and inference queries.

---

## 🎯 Key Learning Outcomes

* Bayesian Network modeling
* Structure Learning with Hill Climbing
* Probabilistic reasoning & inference
* Applying AI techniques to healthcare data
* Comparing expert-based and data-driven approaches

---

## 🏥 Conclusion

This project demonstrates how Bayesian Networks can be effectively applied to real-world medical datasets for:

* Risk prediction
* Decision support systems
* Knowledge representation and reasoning

Both expert-designed and data-driven models produced meaningful and consistent insights into heart disease risk factors.

---
