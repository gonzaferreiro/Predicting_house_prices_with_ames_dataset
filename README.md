# Pridicting house prices with ames dataset

## Introduction

We'll work on this project based on the following business case:

Suppose we work for a real estate company interested in using data science to determine the best properties to buy and re-sell. Specifically, our company would like to identify the characteristics of residential houses that estimate the sale price and the cost-effectiveness of doing renovations.

There are three components to the project:

1. Estimate the sale price of properties based on their "fixed" characteristics, such as neighbourhood, lot size, number of stories, etc.
2. Estimate the value of possible changes and renovations to properties from the variation in sale price not explained by the fixed characteristics. Your goal is to estimate the potential return on investment (and how much you should be willing to pay contractors) when making specific improvements to properties.
3. Determine the features in the housing data that best predict "abnormal" sales.

This project uses the [Ames housing data recently made available on kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

---

## Directions

Though the housing data for this project is very rich, it is not trivial to clean and prepare for modelling. Good EDA, cleaning, and feature engineering were critical to the success of the following modelling stage.

The first two parts of the project consisted of regression problems. There were potentially hundreds of features and plenty of multicollinearities, so regularization was definitely needed.

The second question involved fitting a regression on the residuals of the first model. This is a practice that "covaries out" any effects of the predictors in the first model before investigating the effects of predictors in the second model.

The third section of the project was more challenging and involved dealing with significant class imbalance. This is a common and tricky problem in real-world classification tasks and we used some basic re-sampling techniques to solve this.

## Conclusions

Inside the main notebook, you'll find conclusions throughout the entire document. Feel free to stop at any time to explore the different visualizations used and the code that led to each conclusion.
