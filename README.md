# Forecasting the Stock Market with Watson Studio
Using the IBM Watson Studio and other popular open-source Python libraries for data science, this code pattern provides an example of data science workflow which attempts to predict the end-of-day value of S&P 500 stocks based on historical data. It includes the data mining process, that uses the Quandl API – a marketplace for financial, economic and alternative data delivered in modern formats for today's analysts.



## FLOW
![flow-diagram](https://github.com/ac12644/Stock-Market-prediction-AI/blob/master/architecture.png?raw=true)

## STEPS
- Create a Watson Studio project.
- Assign a Cloud object storage to it.
- Load Jupyter notebook to Watson Studio.
- The sample data provided by Quandl API is imported by the notebook.
- Data imported are refined by Data Refinery and saved to Cloud object storage.
- Using SPSS modeler flow to create forecasts
- Importing the Watson Machine Learning model exported from SPSS modeler flow to Watson Machine Learning.
- Exposing Watson Machine Learning model through an API.
- Application use Watson Machine Learning API to create stock market predicitons.
