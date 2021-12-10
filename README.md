# Bike-Sharing-Demand
### Kaggle competition  - Bike Sharing Demand

![image](https://user-images.githubusercontent.com/7562160/145544439-cb1b5760-32bc-499b-89c8-c85751ad8910.png)

## Report: Predict Bike Sharing Demand with AutoGluon Solution
### Name: Omer Shechter

## General 
This Readme file is the report of my work on the Predicted Bike Sharing Demand. 
Main stages :
1. Connect to Kaggkle and load the data 
2. Initial review of the data 
3. Build a simple model 
4. Submit to Kaggle 
5. Perform an exploratory data 
6. Add Features 
7. 	Add More Features 
8. Review feature importance - remove features 
9. Hyper Tune parameters 
10. Write the report 


## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
There is a need to verify that the output data doesn't contain negative values.
### What was the top ranked model that performed?


![image](https://user-images.githubusercontent.com/7562160/145545579-4cad23d3-5ef5-413c-9a61-0ab1d5e10ead.png)


 
Top Score test was ~43   Top Val score was ~118
Kaggle submission  : 1.38952


## Exploratory data analysis and feature creation
###  What did the exploratory analysis find and how did you add additional features?



#### Histogram of the basic Features
![image](https://user-images.githubusercontent.com/7562160/145545804-dcf6dc1d-b714-4ef3-9782-85ca1e2c24cb.png)


#### Boxplot of all Features 

![image](https://user-images.githubusercontent.com/7562160/145545849-ebe92fc2-427c-47a7-ac27-3b7d21b4b41a.png)

#### Line plot of Bike Demands  

![image](https://user-images.githubusercontent.com/7562160/145545891-6164c674-b624-49cc-9a41-5ba85c092cc8.png)

Note:  Partial plot – full graph is in the notebook 




