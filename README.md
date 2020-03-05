# Final-Project -- > Housing Data 3.0

1. We took multiple variations of Zillow housing data.  

2. Based on our needs we used the Housing ETL Juypter notebook to clean and reshape the data. The pandas Melt function was critical in our cleaning needs- as the dates were columns when we needed them as features in rows. 

3. Also the Housing ETL was used to remap the neighborhoods to the y_test and predicted values for our Random Forest model.Files cleaned new_housing and final predictions.

4. 20200204_CHIHOUSING.ipynb was our Random Forest model- we reused this model for 2 different datasets.  The main iteration used new_housing.csv with 2 years worth of data.  We also implemented a different dataset of new_housing to provide a more robust dataset of 18 years; however, this data was inconclusive due to overfitting.

5. Model_comparison utilized new_housing for a neural network modeling.  We used a base code from towardsdatascience.com and attempted to implemented our own variant.

6. Neighborhood Regression.ipynb was a regression model looking at 18 years worth of crime and housing for one specific neighborhood.

7. App.py is our flask app that analyzes the larger dataset of Zillow data- a break down of housing price by neighborhood and number of bedrooms.
