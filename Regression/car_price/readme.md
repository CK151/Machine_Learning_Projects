# Car Price Prediction: Regression Problem
This project is conducted to predict car prices based on some features, I actually got saw the project from kaggle and worked to improve the model using lesser features
### Data Source
[Car Price Prediction](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction?select=CarPrice_Assignment.csv)

### About the dataset
The dataset contains 26 columns including the index and target variable.
I performed some feature extraction which was my first time doing it thanks to the ✊ [ZABIHULLAH18 kaggle notebook](https://www.kaggle.com/code/zabihullah18/car-price-prediction#The-End-%F0%9F%A4%9D%F0%9F%8E%89%F0%9F%A4%9D%F0%9F%8E%89)

I can say that this project is unique in it's own way because i have to transform some of the features to reduce the number of different classes. 
#### Oversampling and Undersampling
The features were not actually balanced however i worked with them like that however i recommend that if you want to experiment you should Oversampling rather than downSample 

### Converting categorical variables
I manually converted some categorial variable by using the replace method in pandas, please note that this can easily be done using the get_dummies method or just directly using onHotEncoding to fix this.

### Variance inflation Factor (VIF)
After seeing the correlation matrix i noticed that most of out data are highly correlated and needed to be dealt with, so i used the VIF method to eliminate most of the features just have those that the VIF score are below 10 and above 1, the features i ended up using are:
- Symboling (safety)
- Compresion ratio
- Horsepower
- Highwaympg

### Feature Scaling
I used the standard scaler method which works fine for both normally distributed other types of distribution. I subsetted the cleaned data and then performed the scaling on just the features i got from the VIF, because scaling categorical data will result in loss of meaning for our data.

#### Algorithms used
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

At the end ☄️ Random Forest Regressor came out with 92.5% whic is a bit higher than the 💥 Linear Regressor which has 92.0% R2 score, beating the XGBoost Regressor which has 91.2%🤭.

🔌 Go through the excel file to read meaning to the columns

I hope will have a 😇 nice time on the notebook, feel free to reach out to me if you find something unclear 🤔 or have a few suggetions on how to improve the model 🫡



## 🚀 About Me
I'm a full stack Datascientist, learning day by day, trying to improve myeself

### Contacts
- Email: andersonoki15@gmail.com
- X: @Chandoki15, [Profile](https://twitter.com/Chandoki15)

