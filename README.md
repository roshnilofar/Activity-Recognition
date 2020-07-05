## Activity-Recognition
### Activity Recognition using Random Forests in R

## Practical Machine Learning Project
Roshan Nilofar Iqbal
7/4/2020

# Executive Summary

## Introduction

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement – a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. In this project, your goal will be to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. More information is available from the website here: http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har (see the section on the Weight Lifting Exercise Dataset).

## Aim
The goal of this project is to predict the manner in which subjects did the exercise. This is the “classe” variable in the training set. The model will use the other variables to predict with. This report describes: * how the model is built * use of cross validation * an estimate of expected out of sample error

## Data

The training data for this project are available here:

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

The test data are available here:

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv

## Detailed Information
Six young health participants were asked to perform one set of 10 repetitions of the Unilateral Dumbbell Biceps Curl in five different fashions:

*(Class A):exactly according to the specification
*(Class B): throwing the elbows to the front
*(Class c): lifting the dumbbell only halfway
*(Class D): lowering the dumbbell only halfway
*(Class E): throwing the hips to the front
Read more: http:/groupware.les.inf.puc-rio.br/har#ixzz4Tjqh65ze

## Reference
Velloso, E.; Bulling, A.; Gellersen, H.; Ugulino, W.; Fuks, H. Qualitative Activity Recognition of Weight Lifting Exercises. Proceedings of 4th International Conference in Cooperation with SIGCHI (Augmented Human ’13). Stuttgart, Germany: ACM SIGCHI, 2013.
