🏠 Housing Prices Prediction

This project is based on the Kaggle House Prices: Advanced Regression Techniques
 competition. The goal is to build a machine learning model that can predict the final price of a house based on various features describing the property.

📌 Project Overview

House prices are influenced by multiple factors such as location, quality, area, year built, and other amenities.
This project applies data cleaning, visualization, feature engineering, and regression modeling to predict house prices accurately.

🔧 Tech Stack

Python 3.10+
Pandas / NumPy → data manipulation
Matplotlib / Seaborn → data visualization
Scikit-learn → preprocessing, model building, and evaluation
XGBoost / LightGBM / RandomForest (optional advanced models)

📊 Workflow

-Data Exploration
Load training and test datasets
Explore structure, distributions, and missing values

-Data Cleaning & Preprocessing
Handle missing values
Convert categorical features
Outlier detection and removal
Feature scaling

-Exploratory Data Analysis (EDA)
Correlation analysis with SalePrice
Heatmaps, scatterplots, and boxplots to understand feature importance

-Modeling

Train baseline regression models (LinearRegression, etc)
Evaluate advanced models (RandomForestRegressor, XGBoost)
Cross-validation and hyperparameter tuning

-Evaluation

Metrics: Root Mean Squared Error (RMSE) (as used in Kaggle)
Compare model performances

🚀 How to Run

Clone the repo and install dependencies:

git clone https://github.com/ATWIINETIRZAH/Housing-prices-prediction.git
cd housing-prices-prediction
pip install -r requirements.txt


📈 Results

Identified top features affecting house prices:
OverallQual, GrLivArea, GarageCars, TotalBsmtSF, etc.

Achieved competitive RMSE score on Kaggle test set.

📚 References

Kaggle Dataset: Housing Prices Competition for Kaggle Learn Users
Scikit-learn documentation: https://scikit-learn.org/stable/


✨ This project was created as part of a Kaggle Hackathon challenge to improve regression and data science skills.