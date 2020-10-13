# Used Car Price Regression Model


![picture1](https://raw.githubusercontent.com/twhipple/Used_Car_Price_Regression_Model/main/Images/johnathan-ciarrocca-x3HRBLzCmBU-unsplash.jpg)

*How much does a used Toyota cost? Source: Johnathan Ciarrocca, Unsplash.com*


## Intro
This repo is my attempt to create a linear regression model for used cars.
This dataset comes from a collection of UK Used Car listing that were scraped and assembled for use. I chose to start off with the Toyota dataset because I happen to own one myself. The price is in English Pounds but for the use of this notebook I don't think I will be dealing with it - though I suppose I could figure out how to determine the exchange rate into Dollars depending on the year.


## README Outline
* Introduction 
* Project Summary
* Repo Contents
* Prerequisites
* Feature and Definitions
* Results
* Future Work
* Built With, Contributors, Authors, Acknowledgments


![picture2](https://raw.githubusercontent.com/twhipple/Used_Car_Price_Regression_Model/main/Images/Screen%20Shot%202020-10-13%20at%208.59.55%20AM.png)

*Boxplot of Price and Model Types*


## Repo Contents
This repo contains the following:
* README.md - this is where you are now!
* Used_Car_Price_Notebook.ipynb - the Jupyter Notebook containing the finalized code for this project.
* LICENSE.md - the required license information.
* toyota.csv - the file containing the dataset in csv.
* CONTRIBUTING.md 
* Images



## Libraries & Prerequisites
These are the libraries that I used in this project.
* import pandas as pd
* import numpy as np
* import matplotlib.pyplot as plt
* %matplotlib inline
* import seaborn as sns

* from sklearn.preprocessing import StandardScaler

* import statsmodels.api as sm
* from sklearn.model_selection import train_test_split
* from sklearn.linear_model import LinearRegression
* from sklearn.metrics import mean_squared_error
* from sklearn.model_selection import cross_val_score

![](https://raw.githubusercontent.com/twhipple/Used_Car_Price_Regression_Model/main/Images/Screen%20Shot%202020-10-13%20at%209.00.24%20AM.png)

*Different Transmission Types in the dataset*


## Features
These are the features of this dataset.

* 5 numerical columns: 'price', 'mileage', 'tax', 'mpg' and 'engineSize'
* 3 categorical columns: 'model', 'transmission' and 'fuelType'
* 1 date column: 'year'


## Models
I will use a Linear Regression Model after converting the categrical features and scaling the numerical features.


## Conclusions
From my EDA, I can conclude that a car's price is indirectly related to it's mileage. And the size of the engine is a good predictor of price since there is a direct relationship.


![](https://raw.githubusercontent.com/twhipple/Used_Car_Price_Regression_Model/main/Images/Screen%20Shot%202020-10-13%20at%209.16.16%20AM.png)

*Mileage vs Price Reg Plot*


## Future Work
My basic model seemed to have some difficulties because of the number of columns - mostly due to all the different models involved.


![Picture3](https://raw.githubusercontent.com/twhipple/Used_Car_Price_Regression_Model/main/Images/roadside-assistance-required-jamie%20brelsford.jpg)

*Roadside assistance required! Source: Jamie Brelsford, freeimages.com*


## Built With:
Jupyter Notebook
Python 3.0
scikit.learn

## Contributing
Please read CONTRIBUTING.md for details

## Authors
Thomas Whipple

## License
Please read LICENSE.md for details

## Acknowledgments
Kaggle - 100,000 UK Used Car Data set
