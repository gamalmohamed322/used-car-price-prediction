# Used Car Price Prediction

## Overview
This project predicts used car prices using machine learning regression models. The model uses vehicle features such as year, mileage, fuel type, transmission, engine, power, and owner type to estimate the price of a used car.

## Problem Statement
Used car prices depend on many factors, which makes pricing difficult. This project builds a machine learning pipeline to predict used car prices based on vehicle specifications and historical data.

## Dataset
The dataset contains used car information with features such as:
- Car name
- Location
- Year
- Kilometers driven
- Fuel type
- Transmission
- Owner type
- Mileage
- Engine
- Power
- Seats
- Price

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Data cleaning
2. Handling missing values
3. Removing duplicates
4. Converting text-based features into numerical values
5. Encoding categorical variables
6. Outlier handling
7. Feature scaling
8. Training multiple regression models
9. Hyperparameter tuning
10. Feature importance analysis

## Models Tested
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Polynomial Regression
- Gradient Boosting Regressor

## Best Model
The tuned Gradient Boosting Regressor was selected as the final model because it achieved the best overall performance and showed strong generalization on the test data.

## Key Learnings
- Data preprocessing has a strong impact on model performance.
- Feature engineering improves prediction accuracy.
- Outlier handling helps make predictions more stable.
- Comparing multiple models helps choose the best approach.
- Feature importance helps explain which factors affect car prices the most.

## How to Run
1. Clone the repository:

```bash
git clone https://github.com/gamalmohamed322/used-car-price-prediction.git
Install the required libraries:
pip install -r requirements.txt
Open the notebook:
jupyter notebook used_car_price_prediction.ipynb
My Contribution
Cleaned and preprocessed the dataset
Converted mixed text features into numerical values
Trained and compared multiple regression models
Tuned the best-performing model
Analyzed feature importance
Helped prepare the final presentation
