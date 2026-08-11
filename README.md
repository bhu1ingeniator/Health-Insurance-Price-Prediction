# Health Insurance Price Prediction

A machine learning application that predicts **health insurance prices** based on customer and health-related information.

The project uses a **Gradient Boosting model** with a **Streamlit** interface to allow users to enter their details and receive an estimated insurance price.

## Overview

Health insurance costs can vary depending on factors such as age, BMI, smoking status, number of children, gender, and region.

This project demonstrates how machine learning can be used to build a regression-based insurance price prediction system.

The application provides an interactive interface where users can enter their information and generate a predicted insurance price.

## Features

- Predict health insurance prices
- Interactive Streamlit interface
- Gradient Boosting machine learning model
- Numerical and categorical feature handling
- Feature scaling using StandardScaler
- Real-time prediction through user inputs

## Tech Stack

- **Python**
- **Pandas** — data manipulation
- **NumPy** — numerical operations
- **Scikit-learn** — machine learning and feature scaling
- **Streamlit** — interactive web application
- **Pickle** — loading the trained machine learning model

## Input Features

The application uses the following inputs:

| Feature | Description |
|---|---|
| Age | Age of the individual |
| Gender | Gender of the individual |
| BMI | Body Mass Index |
| Smoker | Smoking status |
| Children | Number of children |
| Region | Residential region |

The application processes these inputs into numerical features before passing them to the trained model.

## Machine Learning Workflow

```text
User Input
    │
    ▼
Feature Encoding
    │
    ▼
Feature Scaling
    │
    ▼
Gradient Boosting Model
    │
    ▼
Predicted Insurance Price
