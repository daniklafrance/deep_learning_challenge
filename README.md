# Deep Learning Challenge

## Description

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup. From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. 

## Getting Started

#### The instructions for this Challenge are divided into the following subsections:

* Step 1: Preprocess the Data
* Step 2: Compile, Train, and Evaluate the Model
* Step 3: Optimize the Model
* Step 4: Write a Report on the Neural Network Model
* Step 5: Copy Files Into Your Repository

## Setup

* scikit-learn 1.0.2
* tensorflow 2.11.0
* pandas 1.0.5
* python 3.7.7

## Dependencies

* from sklearn.model_selection import train_test_split
* from sklearn.preprocessing import StandardScaler
* import pandas as pd
* import tensorflow as tf

## Grading

* Preprocess the Data (30 points)
* Compile, Train and Evaluate the Model (20 points)
* Optimize the Model (20 points)
* Write a Report on the Neural Network Model (30 points)

# REPORT

## Explain the purpose of the analysis

The purpose is to create a model that can predict, based on available data (features), if an applicant will be successful if funded by Alphabet Soup.


## Answer all 6 questions in the results section:


### What variable(s) are the target(s) for your model?
* The variable IS_SUCCESSFUL is the target for my model.


### What variable(s) are the features for your model?
* The feature variables are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS AND ASK_AMT.


### What variable(s) should be removed from the input data because they are neither targets nor features?
* The variables I removed are EIN and NAME.


### How many neurons, layers, and activation functions did you select for your neural network model, and why?

##### Model 1
![Alt text](image-3.png)

##### Optimization 1
![Alt text](image-5.png)

##### Optimization 2
![Alt text](image-6.png)

##### Optimization 3
![Alt text](image-7.png)

* In model 1, I started off with the shown example and then built upon that for the optimization models. I tried to vary the changes to see how the performance would be impacted. Below is how each model performed.


### Were you able to achieve the target model performance?

##### Model 1
![Alt text](image.png)

##### Optimization 1
![Alt text](image-1.png)

##### Optimization 2
![Alt text](image-2.png)

##### Optimization 3
![Alt text](image-8.png)

* I was not able to achieve the target of 75% accuracy. 


### What steps did you take in your attempts to increase model performance?
* Simply put, I made adjustements to the model in the order of my coding. I started adjusting the data to see what the impact would be. Then I moved on to the layers and neurons of the model. Finally, I made adjustments to the epochs.


## Summarize the overall results of your model
* I was not able to increase performance of the original model. Accuracy ended up being 0.7252, 0.7241, 0.7236 and 0.7233 respectively. 

## Describe how you could use a different model to solve the same problem, and explain why you would use that model
* My next step would be to run the KERAS TUNER model on the data to find the optimal settings.

## Authors

Danik Lafrance https://github.com/daniklafrance

## References

IRS. Tax Exempt Organization Search Bulk Data Downloads. https://www.irs.gov/Links to an external site.