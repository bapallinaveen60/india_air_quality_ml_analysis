Air Quality Prediction Using Weather Data – Indian Cities

This project analyzes the relationship between weather conditions and air pollution (PM2.5) across Indian cities using data analysis and machine learning.

📌 Objectives

Explore air quality patterns across cities

Understand correlations between pollution and meteorological factors

Visualize spatial pollution distribution

Build ML models to predict PM2.5 levels

📊 Dataset

Source: Kaggle – Weather and Air Quality of Indian Cities
Records: 74 cities
Features: Weather variables, pollutants, geographic coordinates

🔍 Exploratory Analysis Highlights

Northern cities show the highest pollution levels

Strong correlation between PM2.5, PM10, and CO

Pollution increases at lower temperatures due to atmospheric inversion

🤖 Machine Learning Models Tested

Linear Regression, Ridge, Lasso

Support Vector Regressor (SVR)

KNN Regressor

Random Forest ⭐

XGBoost

LightGBM

🏆 Best Model

Random Forest achieved the highest performance:

R² Score: 0.74

MAE: 13.87

📈 Feature Importance

Temperature, cloud cover, humidity, and wind features were the strongest predictors, showing that meteorological conditions strongly influence pollution levels.

⚙️ Model Optimization

GridSearchCV was used to tune Random Forest hyperparameters. Performance remained similar due to limited dataset size, suggesting that more data would further improve predictions.

🛠 Tech Stack

Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly
Scikit-learn, XGBoost, LightGBM

🚀 Future Improvements

Use time-series pollution data

Add traffic & industrial emission data

Deploy as an air-quality prediction dashboard
