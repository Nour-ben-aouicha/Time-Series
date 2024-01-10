# 📈 Time Series Project Highlights 📈

## Dataset 1: MRTSSM4413USN
- **Data Exploration:** Loaded data from the "fredr" library, checked for missing values and outliers.
- **Correlation Analysis:** Identified a correlation between time series values and past values.
- **Seasonal Patterns:** ACF plot revealed seasonal spikes, indicating a periodic pattern.
- **Linear Adjustment:** Fitted a linear regression model to adjust for linear trends.
- **ARIMA Modeling:** Explored stationarity, evaluated candidate models, and selected ARIMA(3,1,2) with drift.
- **Forecasting:** Utilized the chosen model for future stock price predictions.

## Dataset 2: HOOVMN03JPM661N
- **Data Handling:** Loaded the dataset, focused on date and value columns for time series analysis.
- **Outlier Removal:** Detected and removed outliers below the threshold of 70.
- **Correlation Discovery:** Lag plot indicated a correlation between values and past values.
- **Segmented Linear Regression:** Adjusted the time series using segmented linear regression.
- **Residual Analysis:** Modeled residuals, checked for stationarity, and evaluated candidate ARIMA models.
- **Model Selection:** Chose ARIMA(1,0,5) with non-zero mean for its robust fit.
- **Forecasting:** Generated future predictions using the selected ARIMA model.

## General Phases for Both Datasets:
- **Diagnostic Checks:** Conducted Ljung-Box tests, ACF, and PACF plots for model evaluation.
- **Model Summary:** Extracted and interpreted model summaries, assessing coefficients, significance, and fit.
- **Forecast Visualization:** Utilized the "forecast" library to visualize and understand future stock price predictions.

Feel free to explore the detailed steps in each phase, contribute to the project, and leverage these insights for your own time series analysis! 🚀📊
