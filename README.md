# zomato-Restaurant-data-analysis
🍽️ Restaurant Rating Prediction using Machine Learning


📌 Project Overview

This project builds an end-to-end Machine Learning pipeline to predict restaurant ratings based on features such as cost, number of pictures, reviews, and other attributes.
The solution helps businesses understand key factors affecting customer ratings and supports data-driven decision-making.

Target Audience:

Data Science & ML learners

Recruiters & interviewers

Food-tech and restaurant analytics teams

🎯 Problem Statement

Restaurant owners and food platforms often struggle to identify the factors influencing customer ratings.
This project aims to predict restaurant ratings using machine learning models to improve customer satisfaction, pricing strategies, and business performance.

📊 Dataset Description

Contains restaurant-related features such as:

Cost

Number of pictures

Reviews (textual data)

Ratings (target variable)

Dataset was cleaned, preprocessed, and engineered before modeling.

🔄 Project Workflow

Data Cleaning & Handling Missing Values

Outlier Detection & Treatment

Feature Engineering & Selection

Text Preprocessing (NLP techniques)

Data Scaling & Transformation

Train-Test Split (80:20)

Model Training (Multiple ML Models)

Model Evaluation & Comparison

Hyperparameter Tuning

Model Deployment using Flask

🤖 Machine Learning Models Used

Linear Regression – Baseline model

Random Forest Regressor – Handles non-linearity and feature interactions

Gradient Boosting Regressor – Final selected model due to superior performance

📈 Evaluation Metrics

The following metrics were used to evaluate model performance:

R² Score – Measures how well the model explains variance in ratings

MAE (Mean Absolute Error) – Average prediction error

RMSE (Root Mean Squared Error) – Penalizes large prediction errors

✔ These metrics directly relate to business impact, ensuring accurate and reliable predictions.

🏆 Results

Gradient Boosting Regressor outperformed other models

Hyperparameter tuning improved model accuracy

Final model showed better generalization and lower error

📌 Best Model: Gradient Boosting Regressor

🧠 Model Explainability

Feature importance analysis was performed to identify key drivers of restaurant ratings

Cost and visual content (pictures) significantly influenced predictions

🚀 Deployment

Model deployed using Flask

Trained model saved using joblib

API accepts input features and returns predicted restaurant rating

📌 (Deployment demonstrated in Google Colab environment)

🛠️ Technologies Used

Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

Machine Learning: Scikit-learn

Model Deployment: Gradio

Model Serialization: Joblib
