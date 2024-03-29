# Property price prediction for AirBnB listings_Word2Vec+XGBRegressor

All the work was performed in IPython Notebook format as part of a closed assignment/competition on Kaggle. The aim of the assignment was to predict property prices of AirBnB listings.

Based on the available training set and acquired external data, I created a data preprocessing and feature engineering pipeline. The pipeline included calculations of distance features based on location coordinates using the haversine formula, extracting vector embeddings from text-heavy listing descriptions using Word2Vec autoencoder, and other basic transformations. Then, I trained an XGBRegressor model with best-performing hyperparameters to achieve 0.93 R2 and 20.5 RMSE on training data. My submission placed first on the public leaderboard of the competition with a score of 42.71 RMSE on the test data.

Notebook follows the structure below:
1. Introduction
2. Importing data
3. EDA, data cleaning and preprocessing - Numerical features, Categorical features, Datetime & Location features, Text features (Word2Vec)
4. Feature selection using F-test
5. Benchmark models - Linear Regression, Random Forest Regressor
6. Final model (XGBRegressor) - 5-fold Cross-Validation, Predictions on training dataset
7. Predictions on test data
8. Conclusion
