# TELCO_IBM-CHURN-PREDICTION
* This is a machine learning project that using the open source  TELCO_IBM dataset

## BRIEF CODE DESCRIPTION
* The python programming language was used to train all models. 
* Data was


## CODE AND RESOURCES USED
**Language:** Python

**Packages:** pandas, os, sklearn, imblearn, xgboost, 

## Exploratory Data Analysis
* Numerical as well as categorical data was analysed
* Churn score and tenure months seem to be the strongest indicators or churn likelihood
* There was a strong positive correlation between churn and churn score
* This means the higher the churn score of a data point, the more likely they are to churn
* There was a decent negative correlation between tenure months and churn score
  

* The least useful features seem to be zip code, longitude and latitude. A ranking should look something like this
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



## Data Cleaning

After importing and carrying out EDA on the data, it had to be cleaned

    Parsed numeric data out of salary
    Made columns for employer provided salary and hourly wages
    Removed rows without salary
    Parsed rating out of company text
    Made a new column for company state
    Added a column for if the job was at the company’s headquarters
    Transformed founded date into age of company
    Made columns for if different skills were listed in the job description:
        Python
        R
        Excel
        AWS
        Spark
    Column for simplified job title and Seniority
    Column for description length

EDA
I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights from the pivot tables.
