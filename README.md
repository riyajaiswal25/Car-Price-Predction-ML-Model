# Car-Price-Predction-ML-Model

# Aim

This project aims to predict the Price of an used Car by taking it's Company name, it's Model name, Year of Purchase, and other parameters.

## How to use?

1. Clone the repository
2. Install the required packages

Some packages are:
 - numpy 
 - pandas 
 - scikit-learn

3. Run the "application.py" file
And you are good to go. 

# Description

## What this project does?

1. This project takes the parameters of an used car like: Company name, Model name, Year of Purchase, Fuel Type and Number of Kilometers it has been driven.
2. It then predicts the possible price of the car. 

## Workflow of the project

1. First of all the data was scraped from Quikr.com (https://quikr.com) 

2. The data was cleaned (it was super unclean :( ) and analysed.

3. Then a Linear Regression model was built on top of it which had 0.92 R2_score.

4. This project was given the form of an website built on Flask where we used the Linear Regression model to perform predictions.




## Output:
<img width="918" alt="s1" src="https://user-images.githubusercontent.com/84279900/196031655-ca3aee44-5894-4770-9a85-5822c059a673.png">


<img width="809" alt="s2" src="https://user-images.githubusercontent.com/84279900/196031668-73220ac7-40d0-40e5-a1f9-791ba033bd54.png">
