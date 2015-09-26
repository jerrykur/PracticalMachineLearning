# PracticalMachineLearning Project

Sept 25, 2015

# Contents
This repo contains the files for the final project in the Coursera Practical Machince Learning Course.  
The files are:

* Project.Rmd - RMarkdown project containing R code that produces create a solution to the classification
* Project.html - .html file proded from running knitr on the contents of Project.Rmd

# Description
This project solves the problem of creating a model to classify the performance of 5 accelerometers.
 We used a Random Forest, with K-folder (n=10) cross validation, to calculate the model 
based on a 60% subset of the training data.  This model was validate by using the remaining 40% of 
the training data as a Validation set.  The model showed good accuracy, >98%.  When the model
was used to predict class for the 20 values in the test set it was correct 100% of the time.  

# Background

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount 
of data about personal activity relatively inexpensively. These type of devices are part of the quantified 
self movement - a group of enthusiasts who take measurements about themselves regularly to improve their 
health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly 
do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. 
In this project, your goal will be to use data from accelerometers on the belt, forearm, arm, and 
dumbell of 6 participants. They were asked to perform barbell lifts correctly and 
incorrectly in 5 different ways. More information is available from the 
website here: http://groupware.les.inf.puc-rio.br/har (see the section on the Weight Lifting Exercise Dataset). 

