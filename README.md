# Heart Disease Prediction Using Logistic Regression

## Project Overview
This project involves predicting heart disease using logistic regression, a binary classification model. The goal is to predict whether a person is at risk of heart disease based on various health-related features. The target variable in this dataset is binary: `0` represents a person who is not affected by heart disease, while `1` represents a person who is affected.

The process includes data collection, preprocessing, and model training, followed by evaluating the model's performance on test data.

## Project Structure

- **Data Collection & Processing**: Collecting and preprocessing the heart disease dataset, checking for missing values and ensuring that the data is clean and ready for analysis.
  
- **Target Variable Analysis**: The target variable is binary, where `0` indicates no heart disease, and `1` indicates the presence of heart disease. We analyze the distribution of this variable to understand the dataset better.

- **Data Splitting**: The dataset is split into training and test sets to train the logistic regression model and evaluate its performance.

- **Logistic Regression Model**: The logistic regression model is trained on the training data and then tested on the test data.

- **Model Evaluation**: The performance of the model is evaluated by checking its accuracy on the test data.

- **Predictive System**: Once the model is trained, a predictive system is built, enabling predictions of heart disease risk based on input features.

## Sample Dataset Overview
The dataset includes various health-related features such as age, gender, cholesterol levels, and more. The target variable (`Heart Disease`) is binary:
- **0**: Person not affected by heart disease.
- **1**: Person affected by heart disease.

The dataset is split into training and testing subsets for model evaluation.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3.Run the code: Execute the Python script to train the logistic regression model and analyze the results:
   ```bash
  python heart_disease_prediction.py

## Key Features

- **Binary Classification**: Predicting the presence or absence of heart disease using logistic regression.
- **Data Preprocessing**: Handling missing values and preparing the data for analysis.
- **Training & Testing**: Splitting the dataset into training and test data, and training a logistic regression model.
- **Model Evaluation**: Assessing the accuracy of the logistic regression model on test data.
- **Predictive System**: Building a predictive system to predict the risk of heart disease.

## Conclusion
This project demonstrates the application of logistic regression to predict the likelihood of heart disease. By classifying individuals as either affected or not affected by heart disease, the model can help in early detection and risk management. This predictive system can assist healthcare providers in taking preventive measures to improve patient outcomes.
