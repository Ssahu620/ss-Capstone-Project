# ss-Capstone-Project

Sonal Sahu – Capstone Project:

Goal – To predict revenues for seven Marriott Hotels in 2025.
Data used to train is daily revenues for seven hotels in years 2024 and 2023.
Steps used –

1)	Load full 2023, full 2024, and current 2025 bookings and revenues in Panda dataframes.

2)	Cleaned data using following steps:
a.	Find “NA” values in three dataframes.
b.	Find unique values along with their frequency percentages.
c.	Replace “NA” values to either one of the existing unique values or “UNKNOWN” depending on frequency percentages.
d.	Plot revenues by hotels and years using a bar plot.
e.	Plot revenues by hotels and years using line plot.

3)	To avoid intensive calculations using a subset of data (NYCRI hotel) to create various models. In the final submission I will use data for all other hotels also.

4)	Use date and revenue columns of NYCRI hotel to test if series is stationary using ACF, PACF, and Durbin-Watson test. 

5)	There is one period lag auto-correlation in data series.

6)	Used three models ARIMA, SARIMA, and Decomposition to predict future values.

7)	Since hotel revenues are dependent on both seasonality (time series) and other factors, I am now switching to linear regression to find out which features are most important to predict future values.

8)	Will discuss with Savio whether to continue refining time series models or regression models to get to final results.

9)	Issue – All coding was done using Google Colab. I am not able to save csv files in Github because of large datasize.
