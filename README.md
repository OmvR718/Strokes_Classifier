# Strokes_Classifier
This project implements a Decision Tree Classifier to predict the likelihood of stroke occurrences based on a healthcare dataset. It involves data preprocessing, model training, evaluation, and serialization for later use.

# Stroke Prediction using Decision Tree Classifier

This project is an application of Machine Learning to predict stroke occurrences based on a healthcare dataset. It uses a Decision Tree Classifier built with scikit-learn and provides insights into feature importance and model performance.

## 📊 Dataset

The dataset used is `healthcare-dataset-stroke-data.csv`, which contains patient health metrics such as:

- Gender
- Age
- Hypertension
- Heart Disease
- Marital Status
- Work Type
- Residence Type
- Average Glucose Level
- BMI
- Smoking Status
- Stroke (Target Variable)

## ⚙️ Project Structure

AML_Project/
├── DT/
│ ├── DescionTreeClassfier_Strokes.ipynb
│ ├── healthcare-dataset-stroke-data.csv
│ └── model_stroke.joblib


- `DescionTreeClassfier_Strokes.ipynb`: The Jupyter notebook containing the full code pipeline.
- `healthcare-dataset-stroke-data.csv`: The dataset used for training and evaluation.
- `model_stroke.joblib`: Serialized trained model using Joblib.

## 🚀 Features

- Data Cleaning & Preprocessing
- Handling missing values and categorical encoding
- Model Training using Decision Tree
- Model Evaluation (Accuracy, Confusion Matrix)
- Model Serialization for deployment

## 📦 Requirements

- Python 3.7+
- pandas
- scikit-learn
- matplotlib
- joblib
- seaborn
- numpy

## 📌 Notes
The model is built with interpretability in mind using Decision Trees.

This project is a part of an Applied Machine Learning (AML) coursework or personal learning effort.

