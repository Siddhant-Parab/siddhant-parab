# Diabetes Prediction

Machine learning classification project to predict diabetes using the Pima Indians Diabetes dataset.

## Overview

This project analyzes medical diagnostic data and compares multiple classification models to predict whether a patient has diabetes.

* Dataset: 768 patients, 8 medical features
* Task: Binary Classification
* Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Models Compared

* Logistic Regression
* KNN
* Decision Tree
* Random Forest
* SVM
* Naive Bayes
* Gradient Boosting

## Best Results

| Model                 | Accuracy | F1 Score |
| --------------------- | -------- | -------- |
| KNN                   | 0.7792   | 0.6792   |
| Random Forest         | 0.7727   | 0.6535   |
| Random Forest (Tuned) | 0.7662   | 0.6400   |

## Key Insights

* Glucose was the strongest predictor of diabetes
* BMI and Age also showed strong influence
* Dataset contained class imbalance and invalid zero values
* KNN achieved the best F1 score

## Project Structure

text
Diabetes Prediction/
├── 01_eda.ipynb
├── 02_data_cleaning.ipynb
├── 03_model_building.ipynb
└── data/


## Getting Started

``bash
pip install -r requirements.txt
jupyter notebook
```


**Siddhant-Parab/siddhant-parab** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
