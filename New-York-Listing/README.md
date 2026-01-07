Airbnb New York Listings — End-to-End Data Science Project

This project presents an end-to-end data science workflow applied to New York City Airbnb listings data. 
The purpose is to understand the key factors influencing listing prices and to build a baseline predictive model using clean, interpretable features.
Below is a structured Data Science Pipeline

1. Data Cleaning and Preprocessing
   Inspected data types, missing values, duplicates, and inconsistencies

   Converted mixed-type columns (beds, bedrooms, baths, ratings) into usable numeric formats

   Applied domain-aware realism filters for price, availability, minimum nights, and reviews

   Handled missing values using logical, data-driven strategies rather than blanket imputation

2. Feature Engineering
   Some of the features created were
     -log_price - to address price skewdness

     -days_since_last_review - as a demand recency signal

     -price_per_bedroom to normalize pricing by capacity

     -is_multi_host - to distinguish professional vs indiviidual hosts

4. Exploratory Data Analysis (EDA)
   Analyzed price distributions and justified log transformation

   Studied the impact of:
    -Location (neighbourhood group and neighbourhood).

    -Room type and property capacity.

    -Reviews, ratings, availability, and host behavior.

   Extracted insights using question-driven visualisation.

5. Feature Encoding & Data Preparation

     -Removed identifiers and leakage-prone columns

     -Applied one-hot encoding to categorical variables

     -Prepared clean feature matrices for modeling

     -Performed train-test split to ensure unbiased evaluation

6. Baseline Modeling

    -Built a baseline Linear Regression model on log-transformed prices

    -Evaluated performance using RMSE and R²

    -Interpreted model coefficients to understand directional price drivers
   





  
     
