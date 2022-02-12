#Bengaluru Apartment Price Prediction

In this project, I built an website to predict apartment prices in Bengaluru. The website built in HTML, CSS and Javascript allows users to enter apartment sq. ft. area, bedrooms, bathrooms and location to predict the price.

I was inspired by Zillow.com's Zestimate feature to build a similar one for Benagaluru's housing market.

First step in this project was to take the raw data and make it ready for modelling. To accomplish this, I first cleansed the dataset, performed feature engineering, dimensionality reduction and outlier removal. After the dataset was ready for modelling, I built a machine learning model and then used k-fold cross validation and GridSearchCV to come up with the best algorithm as well as the best parameters. The results showed Linear regression gives the highest accuracy. So, I used linear Regression for prediction. 

In the next step, I wrote a python Flask server to serve HTTP requests made from the UI and predict the home prices. Last setp was to build a simple website using HTML, CSS and Javascript that allows user to enter total area, number of bedrooms, etc to predict the home price. 

![github readme 1](https://user-images.githubusercontent.com/98637927/153724640-7792f598-86f1-457d-bd1f-a6dffcd9c30e.png)
![giithub readme 2](https://user-images.githubusercontent.com/98637927/153724646-02f34b31-c692-4c8f-885f-73d12c357219.png)
