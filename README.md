# Sentiment Analyser
This repository provides a foundational notebook designed to introduce students to categorise messages by means of TF-IDF. The example focuses on a [regression](https://en.wikipedia.org/wiki/Regression_analysis) problem, using [labelled Twitter messages](https://www.kaggle.com/datasets/tariqsays/sentiment-dataset-with-1-million-tweets). The primary goal of this assignment is to recognise whether a message's intent is considered positive, neutral or negative.

![house-price-predictor](https://github.com/Fontys/sentiment_analyser/blob/main/BANNER.jpeg)
*Image by Stable Diffusion: a robot analysing social media messages*

This notebook is intentionally designed as a foundational starting point and does not strictly adhere to established best practices as it is meant as a learning opportunity. This repo belongs to a five part course: 🚗 [Car price predictor](https://github.com/Fontys/car_price_predictor/)   🛳️ [Titanic Survival Rater](https://github.com/Fontys/titanic_survival_rater/)   <続く>   📧 [Sentiment Analyser](https://github.com/Fontys/sentiment_analyser/)   🚲 [Bike Rental Forecaster](https://github.com/Fontys/bike_rental_forecaster/) 

Feel free to learn from the other parts too!

## 📚 Preparation
Please ensure that you are familiar with the following aspects in order to successfully work with this repo and notebook.
 - You know the basics of [scikit-learn](https://scikit-learn.org/stable/getting_started.html)
 - You understand the concept of [TF-IDF](https://www.geeksforgeeks.org/machine-learning/understanding-tf-idf-term-frequency-inverse-document-frequency/)
 - You understand  [Support Vector Classification (SVC)](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)
 - You understand the purpose and value of regression evaluation metrics [Coefficient of determination (R²)](https://en.wikipedia.org/wiki/Coefficient_of_determination) and [Root Mean Square Error](https://en.wikipedia.org/wiki/Root_mean_square_deviation)

## 🎯 Learning opportunities
The following aspects of machine learning are part of this example:
- Loading tabular data and showing descriptive statistics
- Defining a simple regression and training it using sklearn
- Using a validation dataset to gauge the model's training gains
- Evaluating a regression model's performance using standardized evaluation metrics for regression problems.

## 🤔 Considerations for improvement
This notebook is an example on how to get started, it is open for improvements and enhancements. Feel free to clone my work and use it to study and learn. Things to consider if you want to improve this work:
- Analysing the data to understand the data. What does the data tell about the relation to the car prices?
- Preparing the data to make it more suitable for machine learning. How can the data be prepared for better model performances?
- A visualization of the errors at the end would be interesting
- Calculating the R² and the RMSE of this model would help judging the model's performance. What do their values mean in relation to the case? 
- Regression models can be sensitive to the data being distributed normally. Is it in this project? If not, what can we do?

## ⭐ Citation & Star
If you use my work please cite and star ⭐ this repo. Thanks!
> Konings, Hans H.H.M. (2025) "House Price Predictor" GitHub: https://github.com/Fontys/car_price_predictor/
