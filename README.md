# Udacity Nanodegree Capstone Project--Sparkify


### Overview
The objective of the Sparkify company is to detect the users cancellation decision before it happens and provide them with the better offers in order to retain them and in other words reduce the churn rate.

### Approach  
1. Loading the large datasets into Spark and manipulating them using Spark SQL and Spark Dataframes
2. Using the machine learning APIs within Spark ML to build and tune models
3. Integrating the skills that I've learned in the Spark course and Nanodegree program

## Blog
Summary on this project: [Medium post](https://medium.com/@vinay.analytics14/churn-analysis-of-sparkify-72f9c1b17cf9)

### Task and Datasets 
the objective is to predict churned users based on activites and attributes data of them. And deploy the solution on a distributed system.
This workspace contains a tiny subset (128MB) of the full dataset available (12GB) due to computation problem on huge dataset.  

### Summary of Project
Procedures of analysis:  
1. Data Loading and cleaning
2. Data exploration and Understanding
3. Feature engineering
4. Modeling
5. Enhancements
6. Results
7. Conclusion

###Conclusion:  
Four models, logistice regression, Decision Tree, Gradient Bossted Tree and random forest are tested. Decision Tree was found to 
yield better performance (Accuracy score of 84% and 77% on train and test datasets) thus was selected as final proposal.

## Acknowledgement
Thanks to the Udacity team.
