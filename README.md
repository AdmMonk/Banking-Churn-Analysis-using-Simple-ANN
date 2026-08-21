# Customer Churn Prediction

A machine learning project that predicts customer churn using banking customer data. The project covers data preprocessing, feature engineering, neural network classification, model optimization, and deployment using Streamlit.

## Project Overview

The project follows an end-to-end machine learning workflow:

1. Load and explore the churn modelling dataset.
2. Perform basic classification and data preprocessing.
3. Convert categorical variables into numerical values.
4. Standardize the numerical features.
5. Build a neural network using TensorFlow and Keras.
6. Apply dropout layers to reduce overfitting and improve generalization.
7. Experiment with optimizers to achieve better model performance.
8. Train and evaluate the final model.
9. Save the trained model in `.h5` and `.pkl` formats.
10. Build an interactive web application using Streamlit.
11. Deploy the application using Streamlit Cloud.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TensorFlow
* Keras
* Pickle
* Streamlit



## Machine Learning Workflow

### 1. Data Preprocessing

The dataset contains customer banking information along with a churn indicator.

The data is cleaned and prepared before training the model.

### 2. Feature Engineering

Categorical features are converted into numerical representations so they can be used by the machine learning model.

The features are then standardized to ensure that the input variables are on a comparable scale.

### 3. Neural Network

A neural network is built using TensorFlow and Keras for binary classification.

Dropout layers are used to reduce overfitting and improve the model's ability to generalize to unseen data.

Different optimizers are tested to find a suitable configuration for the model.

### 4. Model Saving

After training, the final model is saved in:

* `.h5` format for the trained neural network.
* `.pkl` format for the required preprocessing/model components.

## Streamlit Web Application

The trained model is integrated into a Streamlit web application.

The application allows users to enter customer details and receive a churn prediction.

### Run Locally

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run app.py
```

## Deployment

The application can be deployed using Streamlit Cloud by connecting the GitHub repository and configuring the required files and dependencies.

## Objective

The objective of this project is to demonstrate an end-to-end customer churn prediction system, from data preprocessing and feature engineering to neural network training, model serialization, and web deployment.
