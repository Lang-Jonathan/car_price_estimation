# Car Price Estimation
## Project description
The fictive company *Rusty Bargain used car sales service* is developing an app to attract new customers.  
In that app, you can quickly find out the market value of your car. In order to implement this functionality the company wants an machine learning model which estimates the price based on given parameters.
  
Therefore, Busty Bargain supplied a dataset with car prices and the available parameters technical specifications, trim versions, and prices. 

## Content
Within this project the following steps have been carried out:

- Data loading and inspection
- Data preprocessing
- Feature encoding
- Model performance estimation via crossvalidation (used models: linear regression as sanity check, random forest, LightGBM and Catboost)
- Model building, training and evaluation
- Hyperparameter tuning

## Outcome
Catboost is the fastet and most accurate for this task with a RSME value of 1145.6 on the trainings set