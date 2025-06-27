🚜 Bulldozer Price Predictor — Machine Learning Regression Project
Can machines learn the real value of heavy machinery?
📌 Overview
In the heavy equipment resale industry, accurately estimating the value of machinery like bulldozers can save millions. This project leverages machine learning and real-world auction data to predict the resale price of bulldozers with precision and confidence.

Using techniques from data science and regression modeling, we analyze rich historical data and build models that bring data-driven intelligence to equipment valuation — something once dependent purely on human expertise.

🔍 Problem Statement
Goal: Predict the final sale price of bulldozers based on machine attributes and sale conditions.

Can we automate the appraisal of bulldozers? With thousands of past sales and features like usage hours, year manufactured, model ID, product group, and more, we aim to build a predictive model that minimizes pricing errors and maximizes reliability.

💡 Key Features
🧼 Data Wrangling: Imputed missing values, removed outliers, normalized timestamps, and engineered temporal features (e.g., machine age).

📊 Exploratory Data Analysis (EDA): Visualized trends in usage, pricing, and age over time to uncover key correlations and business insights.

🔍 Feature Engineering: Extracted and transformed features like:

Machine Age (Year of Sale - Year Made)

Product Group & Enclosure Encoding

Sale Month, Day, and Seasonality Effects

🧠 Model Development:

RandomForestRegressor (baseline)

GradientBoostingRegressor (XGBoost / LightGBM)

Linear Regression for interpretability

🛠️ Hyperparameter Tuning: Employed RandomizedSearchCV for efficient optimization of model performance.

📈 Evaluation Metrics:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

🚀 Results
Our tuned model achieved:

✅ R² Score: 94%+ on validation set

✅ RMSLE: Within 0.24484782922365525 of actual price

✅ Business Insight: Predictive power reveals that machine age and product group are the most influential factors in determining price.

📊 The final model is capable of replacing manual appraisal workflows with fast, consistent, and scalable predictions.

📁 Tech Stack
Languages: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, LightGBM

Tools: Jupyter Notebook, Git, Github

ML Techniques: Regression, Random Search, Data Imputation, Feature Importance, Cross-Validation