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

**1.3 Save the data in a tensor friendly format (.npz)**


## 2. Create the machine learning algorithm

I would like to test the result fast in the first run, so using Neural Network with 2 hidden layers, and each layer contain 50 hidden nodes will provide a solid idea of how the result is going to be.


---include model code here---

The model was overfitting as the training loss is always going down, but validation loss fluctuates up and down in each epoch.

To fix the problem, adding an early stopping mechanism (callbacks) will make the model stops trainning before it becomes overfitting

by setting patient = 2, the algorithm stops at 19th epoch with 90% accuracy.





## 3. Test the model


