# AirBNB Boston Data Set Analysis
This project is to analyse the AirBNB Boston dataset to explore and better understand airbnb listings in Boston. How the listings and their pricing is affected by seasonality, neighberhoods and hosts.
Questions the analysis tries to answer:
#### What is the average availability by season? Does the price change by season?
#### Can we predict listing price? What are the main factors influencing a listing price?
#### Are super hosts less likely to get negative reviews than regular hosts?

# Libaries used
Traditional Python libraries:
pandas, numpy, matplotlib and sklearn
For a pre-trained sentiment analysis model
flair and torch
For model training
xgboost

# Files
airbnb_boston.ipynb a jupyter notebook with the analysis steps

# Dataset
AirBNB Boston dataset from Kaggle
The dataset describe the airbnb's listings activity in Boston it includes 3 separate files:
Calendar: including listing id and the price and availability for that day
Listings: including full descriptions and average review score
Reviews: including unique id for each reviewer and detailed comments
https://www.kaggle.com/airbnb/boston

# Blog post describing analysis and results:
https://johnghaly.github.io/udacity-ds-nano-jg/

# Acknowledgements:
Flair pre-trained sentiment analysis model:
https://github.com/flairNLP/flair
Function to transform date into season:
https://stackoverflow.com/questions/16139306/determine-season-given-timestamp-in-python-using-datetime
