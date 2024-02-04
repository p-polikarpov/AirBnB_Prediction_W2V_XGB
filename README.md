All the work has been performed in the IPython Notebook file as part of a closed assignment/competition on Kaggle. The aim was to predict price of AirBnB listings. Use of external data was unlimited.

Notebook follows the structure below:
1. Introduction
2. Importing data
3. EDA, data cleaning and preprocessing
    3.1. Numerical features
    3.2. Categorical features
    3.3. Datetime & Location features
    3.4. Text features - Word2Vec
4. Feature selection using F-test
5. Benchmark models
    5.1. Linear Regression
    5.2. Random Forest Regressor
6. Final model - XGBRegressor
    6.1. K-fold Cross-Validation
    6.2. Fitting the model on the training dataset and making the prediction
    6.3. Feature inspection
7. Predictions on test data
8. Conclusion

Since the dataset included text-heavy descriptions, a data preprocessing pipeline has been created that includes the creation of NLP pipeline.
Apart from basic NLP techniques, I have extracted autoencoded vectors from each descriptive feature using Word2Vec.
in addition, new features which together bring >X% predictive power in the final version of the model where engineered based on both data given in the training dataset and external datasets
