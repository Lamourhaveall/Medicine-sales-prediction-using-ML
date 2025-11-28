📊 Medicine Sales Prediction in iHerb

Predicting medicine product sales using machine learning

📝 Overview

This project focuses on building a machine learning model to predict daily medicine sales on iHerb based on product feedback, historical sales volume, and demand indicators.
The objective is to help businesses forecast demand, optimize inventory, and support more effective data-driven decision-making.

The workflow includes:

Data preprocessing

Exploratory Data Analysis (EDA)

Feature engineering

Model training and evaluation

Model comparison

Final predictions

📂 Dataset Description

The dataset includes:

- Name of product
- Rating
- Number of review
- Price (tenge)
- Old price (tenge)
- Sold
- Demand
- Discount

Data cleaning steps included handling missing values, treating outliers, and encoding categorical variables.

🛠️ Tools & Libraries

Python

pandas, numpy

matplotlib, seaborn

scikit-learn

🤖 Machine Learning Methods

The following models and optimization techniques were used:

Models

Linear Regression – baseline performance

Random Forest Regressor – ensemble method for capturing nonlinear patterns

Hyperparameter Tuning

GridSearchCV – exhaustive parameter search

RandomizedSearchCV – randomized search for faster optimization

📈 Model Performance

The best-performing model achieved:

MAE: 329.10

MSE: 2,920,324.87

R²: 0.8209

This indicates strong predictive performance and a good fit to the data.
