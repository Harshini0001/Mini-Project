## Welcome to predicting house prices repository

### Introduction 
Our team's objective is to the use the price range of HDB flats offered by data.gov.sg and  help individuals who are looking to buy or sell a home to make informed decisions. For example, a home buyer can use a house price prediction model to estimate the value of a property and negotiate the price with the seller. Similarly, a home seller can use a house price prediction model to determine the right price for their property, helping them sell their home quickly and at a fair price.


### Data Processing
Data processing is an important step in machine learning that involves transforming raw data into a form that is suitable for analysis and modeling. Let's take a look at the types of data processing that we have used.

- Data cleaning is the first step in data preprocessing, which involves removing missing or inconsistent data, duplicate values, and irrelevant features. Data cleaning is crucial as it ensures that the data used in the analysis is accurate and complete, which in turn improves the quality of the results.

- Data normalization involves scaling the data so that it falls within a specific range or distribution. This can be done to ensure that different features have equal weight in the analysis or to reduce the effect of outliers.

- Data tranformation (One-hot encoding) is used to convert categorical variables into numerical features that can be used in a machine learning model. Categorical variables are variables that have a limited number of values or categories, such as "room_type" and "town". One-hot encoding creates new binary variables for each category, indicating whether or not a particular category is present in a given data point. Dropping columns is used to remove columns that are not needed or are redundant. In this code, the original "room_type" and "town" columns are dropped after one-hot encoding because they are no longer needed.

- Data Visualisation to represent data in a graphical or pictorial format to help better understand and analyse the data. Example : Heatmap, Histogram, Bar-chart and etc.

### Methodology

The Random Forest algorithm is a popular and powerful machine learning model that is used for regression and classification tasks. It is an ensemble learning method that constructs multiple decision trees and combines their predictions to make a final prediction. The main advantages of using Random Forest are that it is able to handle large datasets with high dimensionality, it is robust to noise and outliers, and it is resistant to overfitting.
To train a Random Forest model, we first need to specify the number of trees (n_estimators) to build, the maximum depth of each tree (max_depth), and the minimum number of samples required to split an internal node (min_samples_split). These hyperparameters can be tuned using cross-validation to find the optimal values that minimize the error on the validation set.

### Experiments 

In this code, the performance of the Random Forest model is evaluated using mean squared error (MSE) and R-squared (R^2) metrics. MSE is a measure of the average squared difference between the predicted and actual values, and it is a commonly used metric for regression tasks. R^2 is a measure of how well the model fits the data compared to a baseline model that always predicts the mean value of the target variable. A higher R^2 value indicates a better fit of the model to the data.
By comparing the performance metrics of the Random Forest model to a baseline model, such as a model that always predicts the mean value of the target variable, we can determine if the model is performing well or not. We can also compare the performance of different models to choose the best one for a given task.

### Conclusion




