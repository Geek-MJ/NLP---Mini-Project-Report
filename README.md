# NLP---Mini-Project-Report
Physician Notetaker: Medical Conversation NLP Pipeline

# Prediction of Heart Disease Using Machine Learning

This project explores the application of machine learning algorithms to predict the presence of heart disease in patients based on clinical data. The primary objective is to analyze the performance of various classification algorithms and determine the most effective model for this healthcare prediction task.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Models Used](#models-used)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Conclusion](#conclusion)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Overview
Heart disease is one of the leading causes of death globally. Early detection through reliable prediction models can significantly improve treatment outcomes. This project implements and compares several machine learning algorithms to develop a predictive model using patient data.

## Dataset
The dataset used in this project is the Cleveland Heart Disease dataset, which includes features such as:
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Serum cholesterol
- Fasting blood sugar
- Resting electrocardiographic results
- Maximum heart rate achieved
- Exercise-induced angina
- ST depression induced by exercise
- Slope of the peak exercise ST segment
- Number of major vessels colored by fluoroscopy
- Thalassemia
- Target (presence or absence of heart disease)

## Preprocessing
- Handled missing values
- Encoded categorical features
- Feature scaling using standardization

## Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- Naive Bayes

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Results
Among the models tested, the Random Forest Classifier yielded the highest accuracy of **91.8%**, outperforming other models in both precision and recall.

## Conclusion
Machine learning algorithms, particularly ensemble methods like Random Forest, provide effective tools for predicting heart disease. These models can assist healthcare professionals in early diagnosis and intervention planning.

## Installation

Clone the repository:
```bash
git clone https://github.com/Geek-MJ/heart-disease-prediction.git
cd heart-disease-prediction
