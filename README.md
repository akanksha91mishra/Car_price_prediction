# Car_price_prediction
# Data Analysis and Prediction of Car Prices based on used car prices data set:
In this project I'm trying to analyze and visualize the used car prices from the dataset available at https://archive.ics.uci.edu/ml/machine-learning-databases/autos/

I'm planning to divide it in four parts:

Data Wrangling 
  -dealing missing values 
  
Exploratory Data Analysis 
  -descriptive statistics 
  -Categorical Data Visualization
  -Numerical data visualization Using Principle Component Analysis 
  -correlation 
  -correlation stats
  
Data Preprocessing
  -One hot encoding to handle categorical data
  -Data Scaling
Model Devlopment
  -Linear Regression
  -Random forest
  -KNN rgressor
  -XGBoost
  -Adaboost
Accuracy Comparision

# Description of Dataset:
  This data set consists of three types of entities: (a) the
  specification of an auto in terms of various characteristics, (b)
  its assigned insurance risk rating, (c) its normalized losses in use
  as compared to other cars.  The second rating corresponds to the
  degree to which the auto is more risky than its price indicates.
  Cars are initially assigned a risk factor symbol associated with its
  price.   Then, if it is more risky (or less), this symbol is
  adjusted by moving it up (or down) the scale.  Actuarians call this
  process "symboling".  A value of +3 indicates that the auto is
  risky, -3 that it is probably pretty safe.

  The third factor is the relative average loss payment per insured
  vehicle year.  This value is normalized for all autos within a
  particular size classification (two-door small, station wagons,
  sports/speciality, etc...), and represents the average loss per car
  per year.
  
 # Analysis of Categorical Data:
 ![image](https://user-images.githubusercontent.com/50083180/66768424-2f8eb280-eed0-11e9-912c-d97ab7a0ab91.png)  
 # Visualizing Mileage across car makers:
 ![image](https://user-images.githubusercontent.com/50083180/66768719-e12de380-eed0-11e9-9f02-6fcc92869f78.png)
 # Box plots:
 ![image](https://user-images.githubusercontent.com/50083180/66768822-1b978080-eed1-11e9-8c6b-b4199c0d529b.png)
 ![image](https://user-images.githubusercontent.com/50083180/66768836-26521580-eed1-11e9-8909-4135971877c4.png)
# Joint Plot Using Principle Component Analysis:
  ![image](https://user-images.githubusercontent.com/50083180/66768986-919be780-eed1-11e9-9330-49046575f9e8.png)

# Conclusion: 
  XGBoost and Random Forest are predicting price of cars with good accuracy.
  
  
  
  
  
