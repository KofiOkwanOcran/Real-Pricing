# BOSTON HOUSING PRICING

# The Task
About this data

The dataset by sklearn on the Boston House Dataset is used here. The goal is to be able to make a price prediction of a house and to determine the factors on which the price depends.

The dataset has the following column names:

    INDUS - Proportion of non-retail business acres per town.
    NOX - Nitric oxides concentration (parts per 10 million)
    RM - Average number of rooms per dwelling.
    TAX - Full-value property-tax rate per \$10,000
    PTRATIO - Pupil-Teacher ratio by town
    LSTAT - \% lower status of hte population.
    CRIM - Per capita crime rate by town.
    ZN - Proportion of residential land zoned for lots over 25,000.
    CHAS - Charles River dummy variable (=1 if tract bounds river; 0 otherwise)
    AGE - Proportion of owner-occupied units built prior to 1940.
    DIS - Weighted distances to five Boston employment centres.
    RAD - Index of accessibility to radial highways.
    B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town.

# Findings
At the end of performing a regressional analysis on the data, it was found that the following 5 predictors influence the changes in price given a threshold point of 0.4.
They are; INDUS,NOX, RM, LSTAT, PTRATIO, and Tax.

### Below are also the five samples predicted using the model.
PREDICTION:  24.3 // REAL:  22.2 // DIFFERENCE:  2.1
PREDICTION:  30.51 // REAL:  33.4 // DIFFERENCE:  -2.89
PREDICTION:  26.93 // REAL:  24.4 // DIFFERENCE:  2.53
PREDICTION:  12.43 // REAL:  5.0 // DIFFERENCE:  7.43
PREDICTION:  15.97 // REAL:  13.4 // DIFFERENCE:  2.57

Click here to view the project.[https://github.com/KofiOkwanOcran/Real-Pricing/blob/master/Real%20Pricing%20Assignment.ipynb]
