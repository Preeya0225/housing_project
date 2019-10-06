# Project 2: Ames Housing Prices  

### Table of Content 

- [Problem Statement](#Problem-Statement)
- [Executive Statement](#Executive-Statement)
- [Data sets](#Data-sets)
- [Data Dictionary](#Data-Dictionary)
- [Conclusion and Recommendations](#Conclusion-and-Recommendations)

## Problem Statement 
Being a Real Estate agent can be tough sometime as we have to help customers to list their home when they want to sell it. In order to give good recommendations and price estimate of homes, it is important to know what could potentially influence home prices. Which features appear to add the most value to a home or what are things that homeowners could improve in their homes to increase the value? Utilizing our data sets from housing sales prices from 2007 to 2010 in Ames, Iowa, this problem is being explored using Linear Regression model. With this approach, we are trying to find relationship between sales price and other features. A successful model would predict sales prices with the least amount of error. We can use the data sets from 2007 to 2010 to test our model for evaluation and make recommendations accordingly. 

## Executive Statement
Using the data from homes in Ames, Iowa, that was sold from 2007 and 2010, we created a model, that can predict sales prices depending on home features. The data sets included approximately 80 features in various data types. The first step was to explore and to clean the data. After cleaning the data and using visualization, outliers were identified and feature engineering of columns were applied. By eliminating outliers and creating new variables such as dummies to represent categorical features of the homes, we are ensuring that all features of the data will be represented during modeling process. Three models were obtained using the cleaned data such as Linear, Ridge and Lasso regression. The models were evaluated using different metrics and conclusions and recommendations were successfully obtained to answer our problem statement. A presentation about this project was presented and can be found [here](./Presentation.pdf).

## Data sets
Ames Housing Prices from 2007 to 2010
- [Training set](./data/train.csv)
- [Test set](./data/test.csv)

## Data Dictionary 
Data Dictionary can be found [here](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt)

## Conclusion and Recommendations
By using different models of regression, we were able to predict sales price within a margin of \$20,000.   
The top 5 features that contributed the most to the predictions are the followings: 
- Size of the house
- Overall quality of the house
- Age of the house
- Finished basement
- Paved driveway

Based on this model, we can assume that these features are the driving factors if it comes to increasing your home value. We can make recommendations to our clients on things they can improve in their homes before selling it. For instance, if they were to have an unfinished basement, we can recommend them to renovate and finish the basement, if they desire to increase their home value. The model can be very useful in the future if we can isolate certain trends or overall quality finishes that improve homes more than others. However, this needs further research with more recent data. This model still needs improvement, because a margin of \$20,000 in error is still relatively high. This means a house can be under-valued by \$20,000 dollar or over-valued by \$20,000. The next step would be making a better model with more data to reduce the margin of error.
