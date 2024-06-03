# TELCO_IBM-CHURN-PREDICTION
* This is a machine learning project that using the open source  TELCO_IBM dataset
* The python programming language was used to train all models. 


## CODE AND RESOURCES USED
**Language:** Python

**Packages:** pandas, Numpy, os, sklearn, imblearn, xgboost, matplotlib, seaborn,

## Exploratory Data Analysis
* Numerical as well as categorical data was analysed
* Based on correlation coefficients Churn score and tenure months seem to be the strongest indicators or churn likelihood
* The least useful features seem to be zip code, longitude and latitude.
* A ranking in terms of feature importance should look something like this
* Churn score
* Tenure months
* Total charges
* Monthly charges
* CLTV
* Latitude
* Longitude
* Zip Code

*Most promising categorical features from exploring pivot tables of all the categorical features

* Contract
* Payment Method
* Online security
* Internet Service
* Tech Support
* Senior citizen

## DATA CLEANING AND PREPROCESSING
* Churn reason feature was dropped due to a 73% being null values
* Other null values were impute and data was scaled and one-hot encoded
* Imblearn was used to oversample the data since churn was heavily imbalanced.
* This significantly improved results


## MODEL TRAINING
* Several models were trained and tuned including Logistic regressor
* Support vector classifier
* XGB classifier,
* Decision tree classifier
* Voting classifier which had all the previous models.
## RESULTS ON TEST SET
* Evaluating based on f1 score
* Best Results Xgboost: 0.857
* 2nd best soft voting classifier: 0.847
