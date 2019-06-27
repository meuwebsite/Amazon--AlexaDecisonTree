
#### Machine Learning - Decision Trees

# Amazon--AlexaDecisonTree

![fb](images/am9.png)


# Background

Running a targetted marketing ads on facebook. The company wants to anaylze customer behaviour by predicting which customer clicks on the advertisement. Customer data is as follows:

Inputs:

* Name
* e-mail
* Country
* Time on Facebook
* Estimated Salary (derived from other parameters)


# Goals

* Split the data in Train and Test
* Train and Test the model in the data set
* Visualize
* Predict Click on the ad


# How to run 

Open Google Colab https://colab.research.google.com/
* File
* Upload Notebook
* Run the Cells


# Proccess

Import the data set and visualize the data

* With Scatter plot
#  
![fb](images/am1.png)

* With Box plot
#  
![fb](images/am3.png)

* With Histogram
#  
![fb](images/am4.png)

Transforming the data and Executing a training Test 
#  
![fb](images/am5.png)

With Confusion Matrix, checking on the accuracy
#  
![fb](images/am6.png)

ploting the boundary using the trained classifier
* Run the classifier to predict the outcome on all pixels with resolution of 0.01
* Colouring the pixels with 0 or 1
* If classified as 0 it will be magenta, and if it is classified as 1 it will be shown in blue 
#  
![fb](images/am7.png)

Ploting all the actual training points
#  
![fb](images/am8.png)

Visualising the Training set results for Tran and Test
#  
![fb](images/am9.png)
