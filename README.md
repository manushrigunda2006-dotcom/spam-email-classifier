# 📧 Spam Email Classifier

## 📌 Project Overview

This project develops a machine learning-based Spam Email Classifier using Natural Language Processing (NLP).

The system classifies messages into two categories:

- Spam
- Ham (Not Spam)

TF-IDF is used to convert text messages into numerical features. Two machine learning algorithms, Multinomial Naive Bayes and Linear SVM, are trained and compared.

## 🎯 Objective

The objective is to automatically identify unwanted spam messages using machine learning and NLP techniques.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- NLP

## 📊 Dataset

The dataset contains messages labeled as:

- `ham` - legitimate messages
- `spam` - unwanted messages

The dataset contains 5,573 messages with two columns:

- Category
- Message

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Label Encoding
   ↓
Train-Test Split
   ↓
TF-IDF Vectorization
   ↓
Machine Learning Models
   ↓
Model Evaluation
   ↓
Final Prediction
