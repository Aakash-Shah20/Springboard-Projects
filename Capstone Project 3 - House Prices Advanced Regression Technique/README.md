House Prices Advanced Regression Technique Analysis 
 - 

Every know and then, one may now a relitive looking to buy a house. Many times, a new owner needs to pay for the home, as they think about differnet features which they want in their house as well. This capstone project goal is predict house sale prices in Ames, Iowa.

Data features include the following: 
- Housestyle, BldgType (type of dwelling), OverallQual (rates the overall material and finish of the house)
- LandSlope (slope of property), LotShape (general shape of property),TotalBsmtSF (total square feet of basement area)
- 1stFlrSF (first Floor square feet), 2ndFlrSF (second floor square feet), Garage Area, Garage Cars
- SaleType (type of sale), SaleCondition (condition of sale)


In HouseSalePricesEDA .ipynb, we read in the heart_disease data file, finding various correlations between our target feeautre of SalePrice and other features to understand how the impact of the house prices wil effect a buying option.

In HouseSalePrices.ipynb, a Pandas HTML report helped us quickly identify outliers, missing data, duplicate rows of data and correlation charts.In addition we selected only spesific important rows which were applicable to the proect goal.

In the Preprocessing, Training, Modeling.ipynb, I had created the rest of the data into dummy variables, so that I can use all of the data when testing, traing ,and splitting. In the modeling stage, I had created six machine learning models to help us the house prices.

The overall results have shown us that model 6: Gradiant Bossting Regressor had the best score. I chose Model 6 becasue it was the highest Mean Squared Error out of all the models and that the zscore was closer to one. 

Credits: 
Dataset from Kaggle,
Kenneth (Springboard Mentor)
