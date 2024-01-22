# House Pricing Assignment
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
> The company wants to know:
>  - Which variables are significant in predicting the price of a house, and
>  - How well those variables describe the price of a house.
> Also, determine the optimal value of lambda for ridge and lasso regression.

## Table of Contents
* Problem Statment
* Reading and Understanding Data
* Exploratory Data Analysis
* Model Building
* Regularisation Techniques
* Interpretation

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Objective: Create a house price prediction model based on independent variables.
- Purpose:
    - Inform management about how prices relate to different factors.
    - Guide strategy adjustments for higher returns.
    - Understand pricing dynamics in new markets.
- Benefits:
    - Informed Decision Making
    - Strategic Focus on High-Return Areas
    - Insights into New Market Pricing Dynamics
- Goal: Develop a reliable model to empower management in making informed decisions and optimizing strategies in the real estate market.
- Additionally, a data dictionary has been provided, offering descriptions and explanations for the attributes or variables present in the dataset.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The R2 score on the train data is almost the same for linear regression, ridge regression, and laso regression models.
- However, regularisation techniques improved the test data R2 score slightly.

  
- The top 5 predictor variables are
    - __GrLivArea__: Above-grade (ground) living area square feet
    - __house_age__: The age of the house is basically a difference between the year built and the year sold.
    - __Total BsmtSF__: Total square feet of basement area
    - __Neighborhood_Crawfor__: Crawford
    - __Neighborhood_NridgHt__: Northridge Heights
- Expect the remaining 4 predictors to have positive coefficients, which indicate that an increase in these values will increase the price of the house.
- __House_age__ has a negative coefficient, which means an increase in age will reduce the price of the house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Acknowledgements
As part of IIT Bangalore's AI/ML Executive Programme, I worked on this project.


## Contact
Created by  https://github.com/Sai-Krishna-Rali - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
