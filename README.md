# Breast Cancer Prediction MachineLeaning-Pandas
# Overview

The data I used was about breast cancer, which had many different columns containing elements used to test for cancer. The data was all collected and is from Wisconsin. The data does not have any missing values, and all features in the data were recorded with four significant figures. Because there is no missing values each row containts all of the 30 features. The data file as a whole was a csv file you can download called data.csv, if you wanted a deeper look at the data for yourself or wanted the file used in my program go to the link below:

https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

The purpose of writing this software was to learn more about machine learning. I have previous experience working through data using pandas, and have a good overall knowledge of using pandas but I wanted to use that knowledge to dive a little deeper and learn more about basic machine learning. My main goal was to look through the data on my own to find what elements correlated well with the given dignosis. I needed to find that so I can work on my main goal of creating a cancer prediction model. I was able to learn how to train a model and use a desicion tree to create predictions.

## Video Demo

[Software Demo Video](https://youtu.be/dYbyd4V4K3o)

# Data Analysis Results

A question I had to find within the data set before making my prediction model was what elements or columns correlate and impact the diagnosis the most?
I found that the top 5 elements were: concave points_worst, perimeter_worst, concave points_mean, radius_worst , perimeter_mean which all had high correlation with the diagnosis. It was interesting to see that those measurements had the highest correlation, but I can see how they were more imporatant than some of the other elements. 

The main result of working through this data set was creating a prediction model that accurately predicted cancer diagnosis with 90 percent accuracy. The first question was an important step in creating the model because it helped me understand what elements were important to use in my prediction model. I used the top 5 results as well as many others to train and come up with the model. 

# Development Environment

Visual Studio Code

## Programming Language / Libraries

Jupyter Notebook
Python - Pandas
Sklearn

# Useful Websites

* [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
* [w3schools](https://www.w3schools.com/python/python_ml_decision_tree.asp) - Used the machine learning section in general
* [pandas](https://pandas.pydata.org/docs/getting_started/intro_tutorials/index.html)

# Future Work

Things that I want to improve upon my software in the future:
* Increase the model's accuracy when it comes to the prediction 
* Add more functionality to the software
* Create graphs to show the data off more, such as the correlation ( That is why altair is imported but never used)
