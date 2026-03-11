# property-price-prediction
🏠 Property Price Prediction

A Machine Learning based web application that predicts property prices based on key housing features such as location, total square footage, number of bathrooms, and BHK.
The model is trained using a real-world housing dataset and deployed using a Flask backend with an interactive frontend interface.

This project demonstrates the complete Data Science pipeline, including data preprocessing, feature engineering, model training, evaluation, and deployment.

📌 Project Overview

Real estate price prediction is an important problem in the housing market. Accurate price estimation helps buyers, sellers, and real estate agencies make better decisions.

This project builds a predictive machine learning model to estimate house prices based on various features of the property.

The workflow includes:

Data Cleaning

Exploratory Data Analysis

Feature Engineering

Outlier Detection

Model Training

Model Evaluation

Model Deployment using Flask

Web Interface for user interaction

📂 Dataset

The dataset used in this project was obtained from Kaggle and contains housing information such as:

area_type

availability

location

size

society

total_sqft

bath

balcony

price

After preprocessing and feature engineering, the main features used for prediction are:

location

total_sqft

bath

bhk

Target Variable:

price

⚙️ Technologies Used
Programming Language

Python

Libraries

Pandas

NumPy

Matplotlib

Scikit-learn

Flask

Tools

Jupyter Notebook

VS Code

Postman

GitHub

Frontend

HTML

CSS

JavaScript

🧠 Machine Learning Models Used

Several machine learning models were trained and evaluated:

Linear Regression

Lasso Regression

Decision Tree Regressor

After evaluation, Linear Regression performed the best and was selected as the final model.

🔍 Data Processing Steps
1 Data Cleaning

Removed unnecessary columns

Handled missing values

Converted categorical variables

Standardized numerical features

2 Feature Engineering

Extracted BHK from size

Converted total_sqft into numerical format

Created price per square foot feature

3 Outlier Detection

Removed extreme values

Used statistical techniques to filter unrealistic prices

4 Dimensionality Reduction

Reduced location categories with low frequency

Improved model performance

🚀 Model Deployment

The trained model is deployed using Flask API.

Backend Files

server.py
Handles API requests and returns predicted prices.

util.py
Loads the trained model and processes input data for prediction.

🌐 Web Application

A simple frontend interface allows users to input property details and get price predictions.

User inputs:

Location

Total Square Feet

Number of Bathrooms

BHK

The frontend sends these inputs to the Flask API, which returns the predicted price.

📊 Example Prediction Workflow

User enters property details on the webpage

Data is sent to Flask backend

Model processes the input

Predicted price is returned

Result is displayed on the webpage


🧪 API Testing

The API was tested using Postman to verify prediction functionality before integrating it with the frontend.

💡 Future Improvements

Possible enhancements include:

Adding more features such as amenities and location ratings

Improving model performance using advanced algorithms

Deploying the application on cloud platforms

Building a full real estate analytics dashboard

👨‍💻 Author

Aditya Gadiwan

Information Technology Student
SGGS Institute of Engineering and Technology, Nanded

Interested in:

Machine Learning

Data Science

NLP

AI Research
