# Bike Sharing Regresion

## Table of Contents
* [Problem Statement](#problem-statement)
* [Business problem](#business-problem)
* [Dataset](#dataset)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## Problem Statement
The problem statement involves BoomBikes, a US-based bike-sharing provider, facing revenue challenges due to the COVID-19 pandemic. To overcome this setback, the company aims to devise a strategic business plan to boost revenue once the lockdown restrictions ease and the economy recovers. Specifically, BoomBikes wants to comprehend the post-quarantine demand for shared bikes in the American market to position itself favorably amidst competitors and generate substantial profits.

To achieve this goal, BoomBikes has engaged a consulting firm to analyze the factors influencing the demand for shared bikes. The key objectives are:

1. Identifying significant variables that play a pivotal role in predicting the demand for shared bikes.
2. Evaluating the effectiveness of these variables in accurately describing the fluctuations in bike demands.

## Business problem
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Dataset
* Bike Sharing dataset: [day.csv](data/day.csv)
* Data dictionary: [Readme.txt](data/Readme.txt)

## Conclusions
1. More bike rentals on clear weather, on fall, from August to October and in 2019 and less rentals on Sunday.
2. Top 3 features contributing significantly towards explaining the demand of the shared bike are: temperature(temp), year and season (particularly, winter)

## Technologies Used
* seaborn - 0.13.0
* matplotlib - 3.8.1
* pandas - 2.1.2
* missingno - 0.5.2
* numpy - 1.26.1
* statsmodels - 0.14.0
* scikit-learn - 1.3.2

## Acknowledgements
- The project references insights and inferences from live presentation given by [Akashdeep Makkar](https://www.linkedin.com/in/akashdeep-makkar-12110880/) 

## Contact
Created by [Huynh Viet Cuong](https://cuonghv0298.github.io/) - feel free to contact me!