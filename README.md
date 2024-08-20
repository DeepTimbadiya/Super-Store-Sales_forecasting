Project Objective
Goal: This project aimed to apply various quantitative methods, (i.e. Times Series Models and Causal Models) to forecast the sales of the products available in the dataset.

Perform time series analysis to understand the data and trends
Use multiple forecasting models on train dataset
Finally, select the best model to run the test data
Models covered in the notebook include:

Seasonal Naive Model
Holt-Winters Model (Triple Exponential Smoothing)
ARIMA Model and Seasonal ARIMA Models
Linear Regression Model
Conclusion
We considered different time-series models and a regression model for time-series forecasting. From our results, we saw that the linear regression model outperformed the other time-series models. Therefore, for this dataset we could use a regression model, rather than a time-series model to forecast sales. One of the main assumptions of regression models is that the patterns in the historical data will be repeated in the future, and since our data was highly seasonal and had a linear trend, it made sense why the linear regression model outperformed the other models.

![image](https://github.com/user-attachments/assets/3ca0b971-df64-4899-9b90-4d552155749b)

