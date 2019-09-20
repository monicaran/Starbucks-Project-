# **Data Scientist Nanodegree： Data Scientist Capstone**
## Starbucks-Project
----------

1.[Installation](#Installation)

2.[Project Motivation](#project-motivation)

3.[File Descriptions](#file-descriptions)

4.[Results](#Results)

5.[Licensing, Authors, and Acknowledgements](#licensing-authors-and-acknowledgements)

Installation
------
- Python versions 3.*.
- Python Libraries:
    - Pandas.
    - Scikit-learn.
    - numpy.
    - time.
    - matplotlib.
    - seaborn.
    
Project Motivation
------
The purpose of this project is to find how Starbucks customers use the app, and how well is the current offers system. The data sets used in this project contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. From it, we can understand the costumers' behavior and it might help us make better decisions.  
The problem existing is that the offers should be given to customers who mostly complete the offer. The approach is to firstly clean up the data and do some exploratory analysis to see who are the most valuable customers. After that, creating a model helps us predict feature customers and which kind of offers(Buy One Get One Free (BOGO), Discount or informational ) is better to give a current customer by only knowing his/her age, gender, income and the amount they are paying.  

File Descriptions
------
There is one notebook file that have all the work related to the above questions. The data is not available but I showed the data frames and it have some of the data in it. Markdown cells were used to assist in walking through the thought process for individual steps.


Results 
------
In this project, I tried to analyze and make model to predict the best offer to give a Starbucks customer. First step is to explore the data and the second step is the exploratory analysis on the data after cleaning. From the analysis,the most favorite type of offers are Buy One Get One (BOGO) offers and Discount offers. I digged deep to see who and what type of customers we have and noticed that Females tend to complete offers more than males with 56% completion of the offers they received. Where Males completed only 43.18% from the offers they received. In conclusion, the company should give more offers to Females than Males since they have more completed offers. And they should focus more on BOGO and Discount offers since they are the one that tend to make customers buy more.
  
The main findings of the code can be found [here](https://medium.com/@monica.ran5/starbucks-best-offers-predictor-analysis-a7487965f848).

Licensing, Authors, and Acknowledgements
------
The data was given by Starbucks and Udacity.
