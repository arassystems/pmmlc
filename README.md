# Predictive Maintenance Machine Learning Challenge

## About ARAS Systems GmbH & Co. KG

We would like to give committed talents worldwide the opportunity to prove themselves in the area of machine learning and predictive maintenance. Before you start the challenge, please register at mlchallenge@arassystems.de.

ARAS Systems GmbH & Co. KG is a technology company offering development services in the field of industrial automation. Among other things, we develop software for industrial control systems and embedded systems. Besides programming software for control systems ARAS Systems GmbH & Co. KG also develops solutions in the area of Industry 4.0. Therefore, this challenge tackles predictive maintenance for production machines. 

## Introduction to the machine learning challenge

### Winner's award
This challenge shall give machine learning enthusiasts from all over the world a chance to work with us. The winner will be rewarded with attractive prizes - please get in contact with us explicitly. After getting in touch with us, we will share with you our requirements to win the price. Please note, depending on your background we offer different prices.

### Challenge description
Data sets consist of multiple multivariate time series. Each data set is further divided into training and test subsets. Each time series is from a different engine – i.e., the data can be considered to be from a fleet of engines of  the  same  type.  Each  engine  starts  with  different  degrees  of  initial  wear  and  manufacturing variation  which  is  unknown  to  the  user.  This  wear  and  variation  is  considered  normal,  i.e.,  it  is  not considered a fault condition. There are three operational settings that have a substantial effect on engine performance. These settings are also included in the data. The data are contaminated with sensor noise. 

The  engine  is  operating  normally  at  the  start  of  each  time  series,  and  starts  to  degrade  at  some  point during the series. In the training set, the degradation grows in magnitude until a predefined threshold is reached beyond which it is not preferable to operate the engine. In the test set, the time series ends some time  prior  to  complete  degradation.  The  objective  of  the  competition  is  to  predict  the  number  of remaining operational cycles before in the test set, i.e., the number of operational cycles after the last cycle that the engine will continue to operate properly. 

### Usage
The data are provided as a zip-compressed text file with 26 columns of numbers, separated by spaces. Each row is a snapshot of data taken during a single operational cycle; each column is a different variable. 

The columns correspond to: 
1)  unit number 
2)  time, in cycles 
3)  operational setting 1 
4)  operational setting 2 
5)  operational setting 3 
6)  sensor measurement  1 
7)  sensor measurement  2 
... 
26)  sensor measurement  26 

### Challenge
A) Users are expected to train their algorithms using data in the file named train.txt. They must then evaluate  the  RUL  prediction  performance  on  data  provided  in  file  test.txt.  The resulting RUL values must be in top three, to be awarded for the price. 

B) Candidates shall take the data in train.txt and delete column "unit number". Afterwards, an algorithm shall be applied to determine the several unit numbers from there behaviour (clustering).

--> Very Important: Contat us if you don't undestand the challenge well. 
