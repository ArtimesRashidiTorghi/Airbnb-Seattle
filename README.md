# Seattle Airbnb Price Prediction

## Project Overview

This project analyzes Seattle Airbnb listings to predict rental prices based on various features. Two machine learning models, Linear Regression and Random Forest Regressor, have been implemented and evaluated.

## Dataset

The dataset includes various features related to Airbnb listings, such as:

Review Scores (Cleanliness, Communication, Location, etc.)

Property Attributes (Bedrooms, Bathrooms, Beds, Room Type, etc.)

Host Information (Superhost Status)

Price (Target Variable)

## Data Preparation

Handling Missing Values:

Replaced missing values in review-related features with 0.

Dropped rows with missing values in essential columns (host_is_superhost, property_type, bathrooms, bedrooms, beds).

Feature Selection:

Selected only numeric features for model training.

## Exploratory Data Analysis

Plotted histograms of numerical features for insights.

Examined distribution of review_scores_cleanliness.

## Modeling Approach

Two regression models were trained to predict Airbnb price:

Linear Regression

R² Score: 0.46

Mean Squared Error (MSE): 4225.5

Random Forest Regressor

R² Score: 0.48

Mean Squared Error (MSE): 4097.3

## Steps:

Split data into train (70%) and test (30%).

Trained both models using sklearn.

Evaluated models using R² Score and Mean Squared Error.

## Results & Insights

Random Forest Regressor outperformed Linear Regression with a slightly better R² score and lower MSE.

Model performance suggests additional feature engineering or alternative modeling approaches may improve accuracy.

## Dependencies:

Python

Pandas

NumPy

Scikit-learn


