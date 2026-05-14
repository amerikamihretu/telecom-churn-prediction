# 📞 Telecom Customer Churn Prediction using K-Nearest Neighbors (KNN)

## 🧠 Project Overview
This project applies supervised machine learning to predict whether a telecom customer is likely to churn (leave the service) or not. Customer churn prediction is an important real-world problem because it helps companies identify dissatisfied customers early and take action to retain them.

The project demonstrates the full machine learning workflow: data preparation, model training, model evaluation, model complexity analysis, and real prediction on new customer data.

---

## 📊 Dataset
The dataset used contains telecom customer information with features such as:

- Account length
- Total day/evening/night/intl charges
- Customer service calls
- Other customer behavior indicators
- Target variable: **churn** (0 = No churn, 1 = Churn)

---

## ⚙️ Machine Learning Workflow

1. Data loading and preprocessing
2. Feature selection
3. Train/Test split using stratification
4. Model training using **K-Nearest Neighbors (KNN)**
5. Model evaluation using accuracy
6. Model complexity analysis by varying K values
7. Selection of optimal K
8. Final model training
9. Prediction on new unseen customers

---

## 🤖 Model Used
**K-Nearest Neighbors Classifier (KNN)** from Scikit-Learn.

KNN was chosen to clearly demonstrate how model complexity affects overfitting and underfitting by analyzing different values of K.

---

## 📈 Model Complexity Analysis
A graph was plotted showing training and testing accuracy for K values from 1 to 12.

- Small K values showed overfitting
- Larger K values improved generalization
- **Optimal K found: K = 8**

---

## ✅ Results

- Training Accuracy: **0.878**
- Testing Accuracy: **0.854**

These results show good generalization performance without overfitting.

---

## 🔮 Real Customer Prediction
The final model (K = 8) was used to predict churn for new customer entries to simulate real-world usage of the model.

---

## 🛠️ Tools & Libraries
- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn

---

## 🎯 Purpose of This Project
This project was developed as part of my application for **INSA**, demonstrating practical understanding of:

- Supervised learning
- Classification
- Model evaluation
- Overfitting vs underfitting
- Real-world ML application

---

## 📎 Notebook
The full implementation is available in the Jupyter/Colab notebook in this repository.
