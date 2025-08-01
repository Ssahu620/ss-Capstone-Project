Sonal Sahu – Capstone Project:
Goal – To predict revenues for seven Marriott Hotels in 2025. Data used to train is daily revenues for seven hotels in years 2024 and 2023. Steps used –
1.	Load full 2023, full 2024, and current 2025 bookings and revenues in Panda dataframes.
2.	Cleaned data using following steps: 
a. Find “NA” values in three dataframes. 
b. Find unique values along with their frequency percentages. 
c. Replace “NA” values to either one of the existing unique values or “UNKNOWN” depending on frequency percentages. 
d. Plot revenues by hotels and years using a bar plot. e. Plot revenues by hotels and years using line plot.
3.	To avoid intensive calculations using a subset of data (NYCRI hotel) to create various models.
4.	Drop redundant features (Stay Year Calendar", "RoomNights", and "ADR"). Information for these features can be obtained by remaining features.
5.	Add a feature “Month” which will represent the month customer stayed in the hotel.
6.	Use “Group by” method to aggregate revenue by “Stay Date”.
7.	Used Target Encoding to encode all non-numeric features into numerical features.
8.	Plot correlation of every feature in dataframe with the target (Revenue) and note the features that are most correlated with the target variable (Revenue).
9.	Create two new dataframes X (independent features) and Y which is equal to Revenue (target variable).
10.	Split X and Y to training and testing datasets (x_train, x_test, y_train, y_test).
11.	Used Regression model to predict revenue using various features in the datarframe.
12.	Calculate RMSE and compare it to average daily revenue.
13.	RMSE was less than the average revenue, suggesting model is somewhat stable.
14.	Below steps were taken to refine the model further and reduce features. 
15.	Different methodologies were used to get features which are impacting predictions the most. 
16.	Used sequential feature selection to get the best features.
17.	Performance of model is increasing up to six features and then drops substantially.
18.	Used Permutation importance to get the importance of features.
19.	Used SFS and Gridsearch CV to verify feature selection.
20.	Third methodology used to predict Revenue was Random Forest.
21.	Random Forest shows minimum RMSE as compared to other methodologies.
22.	Used hyperparameters of Random Forest model to improve its performance futher.
23.	Using hyperparameters of Random Forest I was able to calculate the lowest RMSE.

