# Uber_Lyft_Analysis

# Summary :-
My target is to explore dataset available on Kaggle. The first part of this project would be exploring the dataset and trying to find a pattern and the second part would be to predict the prices of ride-sharing apps.

1. Analysis : In analysis, we will perform the data cleaning steps, find the correlation between the values of dataset, analyze the patterns, visualizing the patterns, comparing fares between Uber and Lyft and comparing rides of Uber and Lyft.

2. Prediction : In prediction, we analyze the pattern and apply Multiple Linear Regression Algorithm to predict the price according to the several factors.


# Project setup
If you do need to set the project up locally yourself, feel free to follow these instructions:

# Dataset
Uber & Lyft Cab prices:
Cab rides price and Weather dataset 

Overview of Datasets :
- cab_rides.csv : 693072 rows, 10 columns; size : 88.8 MB
Columns: Distance, Cab Type, Time Stamp, Destination, Source, Price, Surge Multiplier,  ID, Product ID, Name

- weather.csv : 6277 rows, 8 columns ; size: 350 KB
Columns: Temperature, Location, Cloud, Pressure, Rain, Time Stamp, Humidity, Wind

# Algorithm used:
Multiple Linear Regression: 
Multiple linear regression goes one step further than Linear Regression, and instead of one, there will be two or more independent variables. If we have two or more variable then it becomes a multiple regression:
Equation :  y = a1 x1 + a2 x2 + a3 x3 +.... +ap xp + a0
Where y = dependent variable or predicted value
	a0 to ap = regression coefficient
	x1 to xp  =distinct predictor variables
Each regression coefficient represents the change in Y relative to a one unit change in the respective independent variable


Requirements :-
```
Python 3.6 or above
Numpy Module
Matplotlib Module
Sklearn 
seaborn
```


# Quickstart
At first you need to download and setup Anaconda Navigator, use jupyter notebook
OR
You can use Google Collab online to run this project.

In a CLI, 
```
git clone git@github.com:goshipra/Uber_Lyft_Analysis.git
cd Uber_Lyft_Analysis
```

Executing Project
- Open project in notebook and run the files individually in the following order:
```
preprocessing_rides.ipynb  --> Preprcessing: Cleaning and analysing Datasets
Comparing_rides.ipynb --> To get a comparison of the rides of both the companies using dataset.
Comparing_fares.ipynb  --> To get a comparison of the ride charges of both the companies using dataset.
price_prediction.ipynb  --> To predict price of both the companies according to the analysis and the model we created.

```


