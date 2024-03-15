
# House Price Description

This is a Multiple Regression problem, carried out for the prediction of house prices 


## Data source

 - [Download the data](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
 


## About the data 

The data gotten from a certain Califonia district, it contains 10 columns and they are;

- Longitude
- Latitude
- housing_median_age
- total_rooms
- total_bedrooms
- population
- households
- median_income
- median_house_value (dependent variable (y))
- ocean_proximit


## Machine Learning Process
The data was pretty clean just had 207 missing values in the total_bedrooms column which i filled up with the mean of the column. Although i filled the missing value with the mean you can try and drop the rows because the total number of rows are 20640 so when you divide 207 by 20640 you will get a value < 5% which means it is save to drop the rows.
Another thing you will observe is that ocean_proximit is of object type so during the preprocessing so they need to be converted to dummy variable i used the pandas dataframe for this process you can also use OneHotEncoding. 

### Machine Learning Models
1. Support Vector Machine
2. Multiple Linear Regression
3. Polynomial Regression
4. Decicon Trees
5. Random Forest
6. XGBOOST


### Best Model
The best models are Random Forest and XGBOOST after hyperparamter tunning and cross validation XGBOOST was the best in terms of performance 


## 🚀 About Me
I'm a passionate young datascienst, making my path step by step untill 🚀

- email: andersonoki15@gmail.com
- X: @Chandoki15

