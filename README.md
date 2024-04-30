# Built ML model using BikeSharing Company dataset

I have found this dataset on kaggle.com, which is of a company who runs a bike rental model based on a automated network. The purpose of building this model is to understand the factor which drives the business of this company and what are the possible factors that can be improved and into which company can invest more so that their business shines.

- Evaluation of model
  1. The r2_score of train dataset is very much similar to the r2_score of test dataset (within 1% range)
  2. The distribution of error terms of y_train and predicted components are concentrated above 0
  3. Their are total 10 features that contribute to the model with near-zero P value and VIF less than 5
  4. Hence, no sign of insignificancy and multi-colinearity

- Insights after building model
  1. Top 3 features that contribute towards the target variable which is booking of bike are:
     1. year, temp and and season_4 which is winter season
  2. So, company can invest more in winter season so that supply chain doesnt hamper 
