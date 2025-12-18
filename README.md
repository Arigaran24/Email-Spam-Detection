# 📧 Email Spam Detection using Machine Learning

## 📌 Project Overview
This project implements an Email Spam Detection system using Machine Learning techniques. The model classifies email messages as **Spam** or **Ham (Not Spam)** by applying text preprocessing, TF-IDF vectorization, and a Naive Bayes classifier.

This project was developed as **Task 1 of the RISE Internship – Machine Learning & AI Track**.

---

## 🎯 Objective
- Automatically classify email messages as spam or non-spam  
- Apply text preprocessing and feature extraction techniques  
- Build and evaluate a machine learning classification model  

---

## 🧠 Technologies Used
- Python  
- Google Colab  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 📂 Dataset
- **SMS Spam Collection Dataset**
- Source: UCI Machine Learning Repository  
- Labels: `spam`, `ham`  

Dataset link:  
https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection

---

## ⚙️ Project Workflow
1. Load and explore the dataset  
2. Perform text preprocessing  
   - Lowercasing  
   - Stopword removal  
   - Tokenization  
3. Convert text data into numerical features using **TF-IDF**  
4. Split the dataset into training and testing sets  
5. Train a **Naive Bayes** classifier  
6. Evaluate the model using accuracy, precision, recall, and confusion matrix  
7. Test the model with custom email inputs  

---

## 📊 Model Evaluation
The model performance is evaluated using:
- Accuracy  
- Precision  
- Recall  
- Classification Report  
- Confusion Matrix  

**Achieved Accuracy:** 90%+ (approx.)

---

## 🧪 Sample Prediction
```python
Email: "Congratulations! You have won a free gift card."
Prediction: Spam 🚨

