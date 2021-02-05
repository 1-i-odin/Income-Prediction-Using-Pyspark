
# Classification Using Pyspark : (Identifying Individuals for Donation)
 
 
## Abstract : 
This Project Focuses on Recognising and Identifying individuals who earn more than $50,000 . Main reason behind this  task is to help Non-Profit Organisations and different Charity events which run on donations and  rely on individuals for donations. Understanding an individual’s income can help a non-profit better understand how large of a donation to request, or whether or not they should reach out to begin with. 
 
## Objective : 
As from research it has been seen that the individuals who are most likely to donate money to a charity are the ones who make more than $50,000. Hence, the primary objective of the project is to predict whether an individual makes more than $50,000 a year or not.
 
In this project, we will use a number of different algorithms to precisely predict individuals’ income.We will then choose the best algorithm from preliminary results and further optimize this algorithm to best model the data.
Our goal with this implementation is to build a model that accurately predicts individuals who earn less than or equal to $50,000 and also who earn more than the same amount.


 
## Data Description :
Data has been taken from UCI Machine Learning Repository and can be downloaded from here.
It has 35,521 observations and 14 attributes : 
[`age,workclass,fnlwgt,education,education-num,marital-status,occupation,relationship,race,sex,capital-gain,capital-loss,hours-per-week,native-country,earnings`]

To correctly identify whether an individual earns more than certain amount or not, one should be able to identify the features on which Income is most likely to depend:

** Below are some of the factors which I think can affect the Income/Earnings:**
* Age: Individuals with higher  age are likely to earn more
* Education: Higher the education level (completed graduation or has doctorate) , more likely to earn greater than $50K a year
* Marital Status: Individuals who are married are more likely to earn a higher amount of income.
* Capital Gain : Individuals who have substantial amount of capital gain in a year , represents they have assets aside from their primary income
* Native Country : Individuals who reside or belong to first world countries are more prone to donate and also earn more.

