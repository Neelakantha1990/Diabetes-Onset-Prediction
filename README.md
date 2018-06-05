# Diabetes-Onset-Prediction
Predicted using Neural Networks and implemented scikit learns GridSearch capability
The test problem we will use in this repository is the Pima Indians Diabetes problem taken from Machine Learning Repository UCI: 
https://archive.ics.uci.edu/ml/datasets/pima+indians+diabetes

This problem is comprised of 768 observations of medical details for Pima indians patents. The records describe instantaneous
measurements taken from the patient such as their age, the number of times pregnant and blood workup. 
All patients are women aged 21 or older. All attributes are numeric, and their units vary from attribute to attribute.

Each record has a class value that indicates whether the patient suffered an onset of diabetes within 5 years of when 
the measurements were taken (1) or not (0).


Steps Followed:-

Implemented  neural networks to predict onset of Diabetes with accuracy of 79%(Approx) on training set with 100  epochs and batch size of 20 neurons

Performed grid search for learning rate and dropout rate to attain accuracy of 78%(Approx) to figure out the best parameter to tune and unto what extent 

Optimized kernel initialization and activation functions for Grid Search to attain  a accuracy on train set of 79.37% 

Performed a grid search to find the optimal number of neurons i.e 16  in each hidden layer achieveing good accuracy score on train set of 79% 

Predicted results on validation set with accuracy of 78% which is closer to train set prediction achieved above , results were tracked using classification report

