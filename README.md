This project is about cleaning, analysing and modelling a large data set of insurance policyholder data to obtain data-driven insights regarding future insruance claims.

1. **Data Loading and Exploration**: I started by loading the insurance policyholder data into a pandas DataFrame. I then explored the data by printing the first few rows and generating descriptive statistics.

2. **Data Cleaning**: I identified and handled missing values, checked for duplicate rows, and ensured that the data types were correct for each column. I also checked for inconsistencies in the data, such as unexpected values in categorical columns and unrealistic values in numerical columns.

3. **Data Visualization**: I used matplotlib and seaborn to create histograms, bar plots, scatter plots, and box plots to visualize the distribution of the data and the relationships between variables.

4. **Data Preprocessing**: I encoded categorical variables using one-hot encoding and scaled numerical variables using standard scaling. I also split the data into a training set and a test set.

5. **Model Training**: I trained a linear regression model, a decision tree regressor, and a random forest regressor on the preprocessed training data.

6. **Model Evaluation**: I evaluated the performance of the models by making predictions on the test set and computing metrics such as mean squared error (MSE), root mean squared error (RMSE), mean absolute error (MAE), and R-squared (R^2).

7. **Feature Importance Analysis**: I used the feature importances provided by the random forest regressor to identify the most important features for predicting claims incurred.

8. **Prediction on New Data**: Finally, I created a DataFrame with specific values for a hypothetical policyholder and used my trained model to predict the claims incurred for this policyholder.
