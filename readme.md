# Audiobook Prediction Using

## Goal
Create a machine learning algorithm that can predict if a customer will buy audiobooks again.

## Data and Link
The data was gathered from an audiobooks app representing 2.5 years worth of engagement.

This data provide information about customers purchase history i.e. book length, review scores, minute listened, last visited date, price, etc.

We want to perform a supervised learning 

Here is the link to the excel file: https://drive.google.com/drive/folders/1yn0MCEoyZHdS9diTtCAyqYwqQlf4Zwqo

## 1. Data Preprocessing

Starting from raw data, there are many NA/errors and categorical variables that we need to handle.


**1.1 Balance the dataset**

**1.2 Divide the dataset into training, validation, and test set**

**1.3 Save the data in a tensor friendly format**


## 2. Create the machine learning algorithm

After the data is cleaned, I performed a descriptive analysis to see if our data is normally distributed and would be a good set to be used to train regression model


We can see that based on Skewness, Mean, Standard deviation, we need to remove some outliers from price and area.


Then I ran another descriptive analysis to see the result after removing outliers.


## 3. Building Linear Regression Model

**3.1 Split training set and test set (80/20)**

**3.2 to see the result please check at:**

