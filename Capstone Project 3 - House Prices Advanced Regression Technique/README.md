House Prices Advanced Regression Tecnique 
 - 

Heart Disease is a continous problem in today's world; And undestanding where disease kicks in is what need look into. 
The goal of the capstone project is to predict whether or not a patient had heart disease. 

Data features include the following: 
- age, sex, cp(cerebral palsy), trestbps(resting blood pressure), chol(cholestrol),
- fbs(Fasting blood sugar), restecg(resting electrocardiographic. results), 
- thalach(maximum heart rate achieved), exang(exercise induced angina),
- oldpeak(exercise relative to rest), slope, ca, and thal     

In Heart Disease Data Wrangling.ipynb, a Pandas HTML report helped us quickly identify outliers, missing data, duplicate rows of data and correlation charts. From this, we had the ability to clean up some data and prepare it for the Exploratory Data Analysis. 

In Heart Disease EDA.ipynb, we read in the heart_disease data file, finding various correlations between age and other features to understand how the impact of high cholestrol may imapct the duration of someones life. 

In the Preprocessing, Training, Modeling.ipynb the Nueral Network models, Linear Regression model, Random Forest Regressor, and Gradient Boost Regressor were explored. In the data, one of the best models which where implented for a suprisingly hgih score was the gradinatn boosting with a 85% validation score on an .05 learning rate. 

The overall results have shown us that there are many mroe highs in the higher ages having cholestrol problems, eventually resulting to heart deisease. As per
reccomendations to prevent heart disease.  

Credits: 
Dataset from Kaggle,
Kenneth (Springboard Mentor)
