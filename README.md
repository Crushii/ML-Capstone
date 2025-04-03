Summary of the Notebook: ML Capstone - Linear Regression on Stock Prices

![linear regression](https://github.com/user-attachments/assets/cb117cf6-77c3-42bb-8c2b-e38c62f0989f)



Objective:
This project applies Linear Regression to predict stock prices based on historical OHLC (Open, High, Low, Close) data. The goal is to understand stock price movement and improve forecasting accuracy.

Dataset Overview:
  Dataset: Yes Bank Stock Prices


  

Features:

        OHLC (Open, High, Low, Close)
  
        Moving Averages (3-month & 6-month)
        Date-based features

  Preprocessing Steps:
  
          Log transformation applied to skewed features.
  
          Data was scaled before applying PCA.
  
          Train-test split performed for model evaluation.

Methodology:
  Feature Engineering:

      Included moving averages (3-month, 6-month) to capture trends.
      
      Handled missing values and outliers.
      
      Principal Component Analysis (PCA):
      
      PCA was applied to reduce dimensionality.

  Model Development:

      Linear Regression applied on PCA-transformed features.

      Model Evaluation: MSE, RMSE, R² score.

  Insights & Visualization:

      Actual vs Predicted Prices plotted.

      Market events (e.g., asset quality reviews, governance issues) correlated with stock price changes.



Libraries Used:

      Python: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Plotly

Machine Learning:

      PCA, Linear Regression, RandomForestRegressor (for comparison)

Data Processing:

Standardization, Train-Test Split
