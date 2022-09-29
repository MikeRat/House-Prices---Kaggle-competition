# House-Prices---Kaggle-competition
The code (in Python) in this project is prepared for competition conducted by kaggle.com
The Housing dataset was compiled by Dean De Cock for use in data science education (2 parts: train.csv, test.csv)
The Goal of the project was to predict the sales price for each house.
Submissions were evaluated on Root-Mean-Squared-Error (RMSE). I achieved score of 0.12620. The code is provided here.

I followed the steps:
 1) Concatenating the dataset into one DataFrame
 2) Target valiable ('SalePrice') normalization (using 'log' and 'sqrt')
 3) Filling lacking values in other variables
 4) Creating categorical variables (using pd.factorize)
 5) Additional variables normalization for those which were skewed > 0.25
 6) Training and predicting models for XGBRegressor, CatBoostRegressor and LGBMRegressor
 7) Taking mean as result of previous step

During my experiments I provided the following activities: feature engineering, variables aggregation and dropping some variables but... It didn't improve results so I rejected those activies from the code.

My working environment: Jupyter lab on Anaconda3.
Enjoy your review!
