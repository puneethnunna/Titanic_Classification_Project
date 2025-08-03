# Titanic_Classification_Project
STEMPeers Internship Program Final Project

This project was developed as part of the **Horizon Quest Internship Program** during the **Summer Machine Learning Class 2025 (STEMPEERS)** under the mentorship of **Bhishan Poudel**. The goal of this project is to apply machine learning techniques to classify whether a passenger on the Titanic would have survived or not based on a variety of features.

## 👨‍💻 Programmer
**Puneeth Nunna**

## 🗓️ Date
**August 2025**

---

## 🚢 Project Overview

Using the famous Titanic dataset, I built a machine learning classification system that predicts the survival outcome of a passenger. This project is designed to demonstrate my understanding of:
- Data preprocessing
- Feature engineering
- Model training and evaluation
- Binary classification algorithms
- Real-time user prediction simulation

---

## 🧠 Models Used

Three different machine learning models were developed and compared:

1. **Logistic Regression**  
   - Simple yet powerful linear classifier
   - Accuracy: ~**0.82**

2. **Random Forest Classifier**  
   - Ensemble method using multiple decision trees
   - Accuracy: ~**0.83**

3. **Decision Tree Classifier**  
   - Rule-based model with a flowchart structure
   - Accuracy: ~**0.78**

Each model was evaluated using:
- Accuracy Score
- Confusion Matrix
- Precision, Recall, and F1-Score (from Classification Report)

---

## 🧹 Preprocessing & Feature Engineering

- Missing values (like `age` and `embarked`) were filled using the median or mode.
- The `deck` feature was dropped due to excessive missing data.
- Categorical features (e.g., `sex`, `class`, `embark_town`) were one-hot encoded.
- Feature scaling was applied using `StandardScaler` for numerical stability.

---

## 📊 Evaluation Metrics

Each model was evaluated on a test dataset (20% split). Here’s a comparison of the results:

| Model                 | Accuracy |
|----------------------|----------|
| Logistic Regression  | ~0.82    |
| Random Forest        | ~0.83    |
| Decision Tree        | ~0.78    |

Random Forest showed the best overall performance in terms of accuracy and balance between precision and recall.

---

## 🔮 Passenger Survival Prediction

Each model includes an **interactive user input section** that allows users to enter a new passenger’s details and get an instant survival prediction.

---

## 📁 Files in This Repository

- `Titanic_Classification_ML_Project.ipynb`: Main notebook with full code, analysis, and results.
- `README.md`: This documentation file.

---

## 💡 What I Learned

- How to clean and prepare real-world data
- Building and comparing multiple ML models
- Evaluating models using classification metrics
- Handling categorical and missing data
- Making predictions based on user input

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy, Scikit-learn)
- Seaborn Titanic Dataset
- Jupyter Notebook
- Machine Learning & Data Science Tools

---
