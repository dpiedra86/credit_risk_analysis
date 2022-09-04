# credit_risk_analysis

#Overview 

The purpose of this project is to give us an introduction on machinelearning. 
It has proven to be quite a challenge since the very start. 
The first thing we had to do in the challenge was to setup a new enviroment to be able to run all libraries needed for machine learning. 
Had a brief introduction in the different types of ML available out there and focused on the supervised machine learning concepts and techniques. 

The objective was to create a prediction for to evaluate risk in the lending of credits from a bank. 

## Results

>Naive Random Oversampling
Instances of the minority class are increased randomly. 
![Naive](https://github.com/dpiedra86/credit_risk_analysis/blob/main/Resources/Naive_Random_Oversampling.png)

>SMOTE Oversampling
Instance from the minority class, a number of its closest neighbors is chosen. 
![SMOTE](https://github.com/dpiedra86/credit_risk_analysis/blob/main/Resources/Smote_Oversampling.png)

>Undersampling 
The size of the majority class is decreased. CLusterCentroids works very similar to SMOTE. 
![Undersampling](https://github.com/dpiedra86/credit_risk_analysis/blob/main/Resources/Undersampling.png)

>Balanced Random Forest Classifier 
A balanced random forest randomly under-samples each boostrap sample to balance it.
![Undersampling](https://github.com/dpiedra86/credit_risk_analysis/blob/main/Resources/Forest.png)

>Easy Ensemble
The balancing is achieved by random under-sampling.
![Easy](https://github.com/dpiedra86/credit_risk_analysis/blob/main/Resources/Easy.png)

## Summary
The results proved to be quite similar with  in the the Sampling models.
The results proved to be more accurate in the ensemble models. 




