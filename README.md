# US-COVID19-Forecasting
The “us_covid19_daily.csv” dataset consists of the details of the covid cases registered in the US on a daily basis. It consists of the details of positive cases, covid deaths and hospitalised cases  on a daily basis. This dataset is particularly used for understanding and forecasting the trend flow of the covid case in the US. You are given the task to perform to build time series model to forecast the Hospitalized count


1. Read the data and do exploratory data analysis. Describe the data briefly and interpret the inferences for each. Initial steps like head() .info(), Data Types, etc .

2.Check for null values. Display appropriate plots for the columns and discuss inference from the plots and summary stats. Check for null values.

3. Display boxplot to find the distribution of the variable ‘hospitalized’ and interpret your inferences. Perform boxplot for month wise distribution of the same and explain your inferences.

4. Perform decomposition of the time series data.

5. Is the data stationary? Plot original data and the rolling mean and standard deviation with window = 15. Perform statistical tests to confirm the stationarity of the data.

6.Plot ACF and PACF plots for the series.

7. Declare the feature vector and split the data into training and test sets. Consider the data before 06-11-2020 for training data and the rest for the test set.

8. Perform Simple average model, Exponential Model, AR, MA and ARIMA Model,Compare the Evaluation metrics of the models and interpret your inferences.
