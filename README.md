# Diabetes Prediction Using Perceptron

This project aims to predict whether a patient has diabetes using the Perceptron algorithm. The dataset used is the [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database).

## Project Overview
This project utilizes a Perceptron model to classify patients as diabetic or non-diabetic based on medical data. The model is trained using features like glucose levels, blood pressure, BMI, and more.

## Technologies Used
- Python
- Pandas
- scikit-learn
- Matplotlib

## Dataset
The dataset used is the [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database), consisting of 768 samples with the following features:
- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age in years
- **Outcome**: 0 for non-diabetic, 1 for diabetic


## Model Training
The following steps are performed:
1. **Data Preprocessing**: The dataset is split into training and testing sets, and scaled using `StandardScaler`.
2. **Perceptron Model**: A Perceptron model is trained using the training set with a maximum of 1000 iterations and a tolerance of `1e-3`.
3. **Prediction**: The trained model is used to predict outcomes on the test set.

## Evaluation
- **Accuracy Score**: Accuracy of the model on the test dataset.
