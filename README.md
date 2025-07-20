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
4)	Used Regression model to predict revenue using various features in the datarframe.
5)	Used Target Encoding to encode all non-numeric features into numerical features.
6)	Used sequential feature selection to get the best features.
7)	Used Permutation importance to get the importance of features.
8)	Used Gridsearch CV to verify feature selection.

Results-
So far model is showing high RMSE. I will speak to my instructor to see how can it be improved.

