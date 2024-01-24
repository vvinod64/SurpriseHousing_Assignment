# Project Name
> Surprise Housing Assignment.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file train.csv.

The company is looking at prospective properties to buy to enter the market. Objective is to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

    Which variables are significant in predicting the price of a house, and

    How well those variables describe the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Top 5 features using Ridge regression are:
	- GrLivArea
	- 2ndFlrSF	
	- TotalBsmtSF
	- OverallQual_Excellent
	- 1stFlrSF	

- Top 5 features using Lasso regression are:
	- GrLivArea
	- OverallQual_Excellent
	- TotalBsmtSF
	- OverallCond_Fair
	- GarageCars


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- jupyter notebook
- python
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements



## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->