# Minor Project- Detecting Parkinson's Disease
### Minor project “Detecting Parkinson’s Disease” submitted in partial fulfilment of the requirements for the award of Bachelor of Technology (B.Tech) of Kaziranga University, Jorhat, Assam.
![alt text](https://github.com/ArindomSharma76/Minor-Project-Detecting-Parkinson-s-Disease/blob/main/images/BLOG_Parkinson%E2%80%99s%20Test%20Recommendation%20Engine.jpg?raw=true)

## Contents in Repository:
1. Project code
2. Youtube link
3. Dataset used
4. Project Report

## Explanation video youtube link: https://youtu.be/Kr6Mk3LuplA    
### or Click on the image below to watch the youtube video:
[![CLICK ON THE IMAGE TO WATCH THE YOUTUBE VIDEO](https://github.com/ArindomSharma76/Minor-Project-Detecting-Parkinson-s-Disease/blob/main/images/Screenshot%20(1806).png)](https://youtu.be/Kr6Mk3LuplA)

## What is Parkinson’s Disease?
Parkinson’s disease is a progressive disorder of the central nervous system. It is a type of movement disorder that can affect the ability to perform common, daily activities. It is a chronic and progressive disease, meaning that the symptoms become worse over time. It affects over 6 million patients worldwide and more than 1 million individuals every year in India. 

## AIM of our project
The goal of this project is to build a model to accurately predict the presence of Parkinson’s disease in an individual, as early detection of this disease could be useful for the identification of people who can participate in trials of neuroprotective agents, or ultimately to try and halt disease progression.
 
## Algorithm used:
We used the XGBoost algorithm. It is a new algorithm for Machine Learning developed with speed and efficiency in mind and is focused on trees to make decisions.

## DataSet used:
The Data Set has been collected from UCI Machine learning Repository. This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD).
Dataset url: https://archive.ics.uci.edu/ml/datasets/parkinsons

## Tools Used:
1. Anaconda Navigator
2. Jupyter notebook
3. Python programming language

## Libraries Used:
1. NumPy
2. Sklearn
3.	Pandas
4.	Matplotlib
5.	Seaborn

## Workflow:
![alt text](https://github.com/ArindomSharma76/Minor-Project-Detecting-Parkinson-s-Disease/blob/main/images/Screenshot%20(1796).png)

1.	Acquiring the dataset
-	We have download the voice sample dataset from UCI Learning Repository and stored in our PC.
2.	Read/Load the dataset
-	Now we will load the dataset from our PC and display it in our code using Pandas data-frame.
3.	Data Pre-processing
-	Here we will explore and examine our dataset (using .info, .corr, .describe methods), remove unwanted values and then visualize our findings using heat-map and bar-chart.
4.	Data Modelling
-	Within this step we will split our data into training and testing part using sklearn library and we will do our prediction using the XGBoost algorithm and find out the Accuracy and Root Mean Square Error of the model’s prediction after that we will again use k-fold cross validation in order to make our model more robust and again find the Root Mean Square Error of the result of validation.
5.	Important feature visualization using XGboost
- Finally, we will visualize and find out the feature that has the highest importance among all the features.

## Results and Conclusion:
1. In our project we have used XGBoost machine learning algorithm.

2. An accuracy of 92.3077% was provided by the machine learning model with RMSE of 0.277350 which is quite good.
![alt text](https://github.com/ArindomSharma76/Minor-Project-Detecting-Parkinson-s-Disease/blob/main/images/Screenshot%20(1775).png)

3. Also on computing the k-fold cross validation to test the model, the model gives Mean Test RMSE of 0.281145 which is very close to the RMSE given by our model initially.
![alt text](https://github.com/ArindomSharma76/Minor-Project-Detecting-Parkinson-s-Disease/blob/main/images/Screenshot%20(1774).png)

4. The proposed model is thus a reliable model to detect Parkinson’s disease due to its efficient accuracy rates.

5. Finally using the XGBoost’s plot_importance() function we have found out that the feature MDVP.Fo(Hz) (i.e. Average vocal fundamental frequency) has the highest importance score among all the features.
![alt text](https://github.com/ArindomSharma76/Minor-Project-Detecting-Parkinson-s-Disease/blob/main/images/Screenshot%20(1773).png)

## Future Scope:
Though the model works efficiently, this is limited by the richness of the dataset with which it is being trained. The selected dataset, has only 197 instances, hence a dataset with more number of samples would help the model generalize better. The proposed model is thus a reliable model to detect Parkinson’s disease due to its efficient accuracy rates.

## Submitted by,

1. Arindom Sharma (ET17BTHCS010)
2. Amrit Kr. Baruah (ET17BTHCS007)
3. Aditya Chakraborty (ET17BTHCS004)
4. Popee Borah (ET18BTHEC011L)
5. Jili Tali (ET18BTHEE017L)

External Mentor: Mr. Amit Bhat (IBM) and
                 Mr. Viqaruddin Surki (IBM)                                                                                                  

Internal Mentor: Mrs. Mousoomi Borah (H.O.D CSE Department, KU)

