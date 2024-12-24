# Machine-Learning
# Brain Stroke Prediction

This project focuses on building a machine learning model to predict the likelihood of brain strokes based on various health and lifestyle factors. The goal is to assist in early detection and prevention of strokes by analyzing patient data.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Results](#results)
- [How to Use](#how-to-use)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)

## Overview
Brain stroke is a leading cause of death and disability worldwide. This project leverages machine learning techniques to predict stroke risk based on features such as age, gender, BMI, and health history.

## Dataset
The dataset used in this project contains the following features:
- Age
- Gender
- Hypertension
- Heart Disease
- Smoking Status
- Body Mass Index (BMI)
- Average Glucose Level
- Work Type
- Residence Type

The dataset is publicly available and has been preprocessed to handle missing values and outliers.

## Data Preprocessing
Key preprocessing steps:
- Handling missing values using mean/median imputation.
- Encoding categorical variables using one-hot encoding.
- Normalizing numerical features for better model performance.
- Splitting the dataset into training and testing sets.

## Modeling
The following models were trained and evaluated:
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- Gradient Boosting

The best model was selected based on metrics such as accuracy, precision, recall, and F1-score.

## Results
- **Best Model**: [Model Name]
- **Accuracy**: XX%
- **Precision**: XX%
- **Recall**: XX%
- **F1-Score**: XX%

The model demonstrated high accuracy and reliable predictions on the test data.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Anuragvarma77/brain-stroke-prediction.git
