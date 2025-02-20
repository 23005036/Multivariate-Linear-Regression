# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step1

Import pandas as pd.

### Step2
Read the csv file.

### Step3
Get the value of X and Y variables.

### Step4
Create the linear regression model anf fit

### Step5
Predict the CO2 emission of a car where the weight is 3300kg and the volume is 1300cm3.

## Step 6
Print the predicted program.

## Program:
```
##Developed by: Beatrice Thomas
## Register number : 23005036

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars.csv")
x=df[['Weight', 'Volume']]
y=df['C02']
regr-linear_model.LinearRegression()
regr.fit(x,y)
print("Coefficient:",regr.coef_)
print("Intercept:", regr.intercept_)
predictedCO2=regr.predict([[3300,1300]])
print("Predicted CO@ for the corresponding weight and volume", predictedC02)

```
## Output:

![Alt text](<Screenshot 2023-12-26 143547.png>)

![Alt text](<Screenshot 2023-12-26 143821.png>)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.