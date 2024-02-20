# Detection-of-Crime-By-Using-Machine-Learning

Abstract

Public places like airports, train stations, theme parks and shopping centers are typically crowded. The flow of people is growing consistently each year with the development of urbanization. This growth causes an increase in the risk of crowd stampedes in public places. To avoid these dangerous situations, the crowd should be monitored, and for detecting in a timely manner, any occurrence of unusual situations. Public safety and security are  main reasons for crowd analysis. Human operators continuously observe the visual screens for detecting any event of interest, which becomes challenging to tackle all the time. Developing an automatic system for detecting anomalous activities insides crowds and facilitating the operators. Constructing a multi-class classification model using a Random Forest classifier to predict the type of major crime committed based on time of day, neighborhood, division, year, month, etc. The dataset includes every major crime committed from 2014-2017* in the city of Toronto, with detailed information about the location and time of offence. The data contains only categorical variables so the modeling process tests both numeric encoding and One Hot encoding, with some improvement with the latter approach. The model performs reasonably well on F1-score (precision and recall) for a five-class classification problem. Though the data set is somewhat unbalanced towards assaults (higher volume), balancing class weights does not materially impact model performance.

Introduction

INTRODUCTION

1.1	PROBLEM DEFINITION

Crime activities like chain snatching and trying to kill person or rare event in a city even though this have servlets camera it is difficult to monitor such type of event by a human. So, a developing a system which will classify the event which it is normal or abnormal event using Machine Learning Technique. If it is abnormal event it will send a alert message to concern department. The main reason for the change in crime detection and prevention lies in the before and after statistical observations of the authorities using such techniques. The sole purpose of this study is to determine how a combination of ML and computer vision can be used by law agencies or authorities to detect, prevent, and solve crimes at a much more accurate and faster rate. In summary, ML and computer vision techniques can bring about an evolution in law agencies.

Machine Learning is the branch of science where computers decide without human intervention. In recent times Machine Learning is being used in various domains one of the examples of such cases is automated or self-driving cars. By Machine Learning algorithms there is a way where this  can predict certain results based upon our inputs given and provide a solution to solving crime cases in India. The two common types of prediction techniques are classification and regression. This crime data prediction is a domain where classification is applied. Classification is a supervised prediction technique and it has been used in various domains like forecasting stock, medicinal area, etc. The purpose is to train the required model to predict the data using the training data set by validation of the test data set. The models which are being used here are Random Forest classification.

1.2	OBJECTIVES

•	The objective would be to train a model for prediction. The training would be done using the training data set which will be validated using the test dataset.
•	Random Forest classification and other algorithm will be used for crime Prediction.
•	This work helps the law enforcement agencies to predict and detect crimes in Toronto with improved accuracy and thus reduces the crime rate.

PROPOSED WORK

The proposed system is made on the basis of the research work that is done by going through various such documentations. Nearly all of the crimes are predicting based on the location and the types of crimes that are occurring in those areas. On surveying previous works, Random Forest tend to give good accuracy so this model is used in this project to predict crimes. The dataset used in this project is from Toronto crime data. The data set contains different types of crimes that being committed in Toronto according to the state and year respectively. This project takes types of crimes as input and gives the area in which crimes are committed as output. The data pre-processing involves data cleaning, feature selection, dropping null values, data scaling by normalizing and standardizing. After data preprocessing the data is free of null values which m ay alter the accuracy of the model significantly and feature selection is used to select only the required features that won’t affect the accuracy of model. After data pre-processing the models chosen i.e.  Random Forest are trained by splitting the data into as train and test data. As the output required is a categorical value classification models are used here. Python language is used for the data prediction.

SYSTEM REQUIREMENTS


2.1	HARDWARE REQUIREMENTS

•	RAM	: 4 GB or above.
•	PROCESSOR : 32/64-bit .
•	Hard disk drive : 250 GB.
•	Many factors impact resources used so we recommend 64 bit processor.
•	Any processor that supports jupyter notebook.




2.2	SOFTWARE REQUIREMENTS

•	Jupyter notebook or any python interpreter.
•	packages like pandas, Numpy, scikit should be installed prior.
•	Python idel 3.7 version
•	Anaconda 3.7
•	Jupiter
•	Google colab



