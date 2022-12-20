# Seoul_Bike_Sharing_Demand_Prediction_Capstone_Project-II
![image](https://user-images.githubusercontent.com/111486947/208640628-acdf772b-334c-4ac7-a4ca-9ee91472b3ed.png)

## Problem Statement
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

## Data Description:
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

## Attribute Information:
• Date : year-month-day

• Rented Bike count - Count of bikes rented at each hour

• Hour - Hour of the day

• Temperature-Temperature in Celsius

• Humidity - %

• Windspeed - m/s

• Visibility - 10m

• Dew point temperature - Celsius

• Solar radiation - MJ/m2

• Rainfall - mm

• Snowfall - cm

• Seasons - Winter, Spring, Summer, Autumn

• Holiday - Holiday/No holiday

• Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

## Data Pipeline:
● Exploratory Data Analysis (EDA): In this part we have done some EDA on the features to see the trend.

● Data Processing: In this part we went through each attributes and encoded the categorical features.

● Model Creation: Finally in this part we created the various models. These various models are being analysed and we tried to study various models so as to get the best performing model for our project.

## Observations:
● Observation 1: In the Model Evaluation Matrices table, Linear Regression, Lasso, Ridge, ElasticNet Decision Tree and XG Boost is not giving great results.

● Observation 2: We are getting the best results from Random forest & GBR with help of r2 score.

## Conclusions:
● We started with loading the data, then we did Exploratory Data Analysis (EDA), null values treatment, feature selection, encoding of categorical columns, and then model building. In all of these models, our accuracy ranges from 13% to 99%, which can be said to be good for such a large dataset. This performance could be due to various reasons like the proper pattern of data, large data, Overfitting of model. 

● After performing variable importance analysis to find the most significant variables for all the models developed with the given data sets. We are getting the best results from With help of Grid SearchCV we get the best result from Gradient Boosting Machine and Random Forest.
