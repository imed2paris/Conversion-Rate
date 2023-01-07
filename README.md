# Conversion rate


## Topic

* In e-marketing, one of the main tasks is to optimise the conversion rate of a site. In other words, during a visit to the site, between the time they enter and the time they leave, we look at whether or not the Internet users have made a purchase.
* Obviously, we want to act on the factors that lead a visitor consulting the site to purchase an item/service.
* The dataset includes some records on users of an anonymous e-commerce site over one year.


## Objective 

* We want to build a model capable of predicting the conversion of a website user, i.e. their propensity to make a purchase: we are clearly faced with a case of supervised learning.
* In this way, we would be able to provide the marketing team (product and marketing department) with advice on how to improve the results.


## Issues

* The dataset contains 300 000 records of an anonymous company with only six features: 
    * two of them are numerical, 
    * two of them are dichotomous qualitative, 
    * the last two are nominal qualitative.
* A full definition of the dataset can be found in the "Data Understanding" files, with a description of each field.
* No other datasets are included in the project.
* We have little information about the users.
* No need to build new features or add records.
* We have to deal with the fact that the data is extremely unbalanced.
* The whole process of cleaning and formatting the data can be found in the "Data Preparation" file.
* At the end of the Data Preparation stage, 4 files are created (files starting with "X_" and "y_") to be used in the Modeling and Evaluation stage.


## Technologies

* I use python packages to solve the problem. In the following, you can find my choice of tools :
    * Pandas for data wrangling, 
    * Seaborn and Matplotlib for data visualisation, 
    * Scikit-learn for modeling.