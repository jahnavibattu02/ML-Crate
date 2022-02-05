## Project Title

Data Analytics Salary Prediction

**Aim of the Project:**  
This project will Create a ML model to classify and predict the salaries of Data Analytics.

**Dataset:**   
https://www.kaggle.com/iamsouravbanerjee/analytics-industry-salaries-2022-india

**Approach:**   
Performed Exploratory Data Analysis on the dataset and Used 3-4 Regression Algorithmns to implement the models and Compared all the algorithms to find out the best fitted one.

**Steps Involved**   
- Import Required libraries.
- Load the dataset.
- Performing EDA on the data like Outlier Treatment, Handling Missing values.
- Identifying Input and Target columns from the dataset.
- Separating Numerical and Categorical columns.
- Scaling the numeric columns and Encoding the categorical columns.
- Splitting the Data into Training and Testing dataset.
- Model Building: We use four algorithms to build the models
    - LinearRegression
    - DecisionTreeRegressor
    - RandomForestRegressor
    - Ridge Regression
    - XGBRegressor   
After fitting these models with the data, we analyze the model using metric mean_squared_error and compare the correlation coefficient r2_score of all algorithms.

**Data Visualization**


**RMSE**   
Linear Regression = 0.012629
DecisionTreeRegression = 0.003997
RandomForestRegressor = 0.003098
Ridge Regression = 0.012628
XGBRegressor = 0.010661 

**Conclusion:**   
Among all the models listed above, we can see that RandomForestRegressor have least RMSE of 0.003098. We can conclude that it is the best fitted model.

**Language and Libraries Used:**
- Python Programmming is used.
- Libraries like Numpy, Pandas, Seaborn, Matplotlib, Scikit-Learn are used.
#    
Code Contributed by Jahnavi Pravaleeka Battu
