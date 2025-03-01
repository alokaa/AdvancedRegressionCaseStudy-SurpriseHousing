# Surprise Housing - Advanced Regression Case Study
 A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. It is required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
* Which variables are significant in predicting the price of a house, and
* How well those variables describe the price of a house.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
It is required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- A linear regression was performed using Ridge and Lasso Regularization.
- Rigde Regression: Ridge Regression is able to achieve the least difference between train and test r2 score. However, because of the number of variables, the model becomes more complex.
- Lasso Regression: Lasso Regression is the model of choice here. The r2 score is good and difference between training and test r2 score is accdeptable. The model is simpler because of fewer variables (excluding the ones the Lasso to which Lasso assigned a 0 co-efficient score).
- Lasso Regression is the model selected model.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.12.1
- Jupyter Notebook 6.5.4
- numpy 1.24.3
- pandas 2.0.3
- matplotlib 3.7.2
- seaborn 0.12.2
- scikit learn 1.3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [Alok Aparanji](https://github.com/alokaa/) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
