
# Enhancing the Airbnb Performance through Price Prediction and Market Segmentation using Machine Learning

Air BnB is a popular online marketplace and hospitality service that allows people to rent or lease short-term lodging accommodations.

The problem is that both hosts looking to rent out their homes and guests looking to purchase are unaware of the market for the properties they are offering.

## Objective
**Host:** Difficult to determine a suitable price for the facilities provided

**Guest:** Desiring the best facilities at the most affordable price

# HOW?
Data-Driven **Price Prediction** and **Market Segmentation** so both host and guest know about the price in the market.

## About Dataset
This dataset is Airbnb data for the United States.
https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata

# Data Pre-Processing
## Missing Values
The missing values in the data need to be cleaned up so that machine learning modeling can be performed effectively later on. 

This is the step i did:
1. Dropping columns with too many null values.
2. Removing rows with null values for specific columns.
3. Deleting duplicate data.

## Handling Outlier
Other outliers are indicating data diversity. However, the 'minimum_nights' column will be reevaluated due to negative values and some in the thousands.

# Exploratory Data Analysis
After that, simple data visualization and Exploratory Data Analysis (EDA) were conducted to gain insights from the data. 

# Machine Learning
Two types of machine learning were performed, namely Price Prediction (regression) and Market Clustering.

## Price Prediction
The goal of price prediction is for the machine to **predict an appropriate price based on the facilities** offered by the Airbnb unit.

After performing modeling, the best model is **Random Forest** with a Training RMSE of 103.06 and a Test RMSE of 289.79.

## Market Segmentation
Market Segmentation dilakukan menggunakan K - Means Clustering dengan nilai K = 6 (dari elbow method dan silhouette).

Then, six types of Airbnb listings with the target variable being "price" will be identified.

# Presentation
Full presentation for this project at:

https://bit.ly/Portfolio_Oktober_2023

# Reference
https://jacobsakhnini.com/project_airbnb.html
https://www.kaggle.com/code/sayanroy729/airbnb-open-data-eda-step-by-step
https://www.kaggle.com/code/lxy21495892/airbnb-eda-pygwalker-demo
https://www.kaggle.com/code/iuliabunescu23/imb-data-analytics-final-project
https://www.kaggle.com/code/kartikexe/airbnb-dataset-eda-and-feature-engineering
https://www.kaggle.com/code/abdelrahmanraslan/airbnb-price-prediction-ml
https://www.kaggle.com/code/dtbingh/what-makes-a-successful-airbnb-business

