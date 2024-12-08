# **Flight Prices Prediction Project**
The project aims to predict flight prices based on a set of features, including airline, flight date, source, destination, route, departure time (Dep_Time), arrival time (Arrival_Time), duration, total stops (Total_Stops), and additional information (Additional_Information).

![dataset-cover](https://github.com/user-attachments/assets/ce835284-0eac-4633-9e4f-a7ee8fae4fab)

## Project steps details 
### 1. Data Import:
+ Download the Flight Prices Prediction dataset from Kaggle.
+ Import and clean the data by handling any missing or incorrect values and remove outliers. 

### 2. Data Analysis:
* Explore data and analyze different features.
* Create visualizations to highlight the relationships between different features and The price of flights .

### 3. Model Building:
* Try different algorithms like: Linear Regression, polynomial Regression, Ridge Regression, Lasso Regression, Random forest, Decision tree, XG-Boost, KNN, SVM.   
* Train the model using the data and evaluate its performance using metrics like: R2-Score, MSE, RMSE, MAE, MAPE.
 
### 4. Model Improvement:
* Improve the model using techniques like cross-validation and feature engineering.
* Compare different models and select the one that provides the best accuracy.

# Data Set 
__________________________________________________________
The dataset for this project can be found [Here](https://www.kaggle.com/datasets/muhammadbinimran/flight-price-prediction/data)

# Results 
___________________________________________________________
Below is a brief description of the results of the models used. 

## ▪ Linear Regression & SVM :
Demonstrated relatively low performance, with low R2-Score values ​​and high error metrics, This suggests that these models might not be the best fit for this task.
______________________________________________________________
## ▪ Polynomial Regression & Ridge Regression :
showed noticeable improvements in performance, with higher R2-Score values and lower error metrics compared to Linear Regression, This reflects these models better adaptability to the data.
___________________________________________________________________
## ▪ Lasso Regression :
demonstrated good performance with high R2-Score values and low error metrics, indicating its capability to reduce complexity and overcome overfitting.
____________________________________________________________________
## ▪ Decision Tree & Random Forest :  
showed excellent performance, with very high R2-Score values and low error metrics, reflecting their ability to generalize well without overfitting the training data.
______________________________________________________________________
## ▪ XG-Boost :
exhibited outstanding performance, with high R2-Score values and low error metrics, making it a strong and effective model for data analysis.
____________________________________________________________________________
## ▪ KNN :
also demonstrated excellent performance, with very high R2-Score values and low error metrics, making it highly suitable.


