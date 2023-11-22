# **Medical Insurance Price Prediction**

## **Introduction**
The code implements a *Medical Insurance Price Prediction* model using regression techniques. The primary objective is to predict insurance charges based on various input features, making it a supervised learning problem.

## **Dataset Information**
The code starts by importing necessary libraries and loading the *medical insurance dataset* from 'medical_insurance.csv'. The dataset includes information such as *BMI, gender, age, number of children, smoking status, region*, and *insurance charges*. The initial exploration involves checking data dimensions, information, and addressing any duplicate values.

## **Exploratory Data Analysis (EDA)**
EDA is performed to gain insights into the dataset's characteristics:
- Features are categorized into *numerical and categorical*.
- Visualizations include pie charts for *categorical feature distributions* and histograms for *numerical features*.
- Feature encoding is applied for *machine learning compatibility*.
- The summary of EDA outlines key observations regarding the distribution of *age, BMI, number of children, smoking status, region*, and *gender*.

## **Feature Engineering**
A *correlation matrix* is generated and visualized to understand relationships between features. The focus is on the strong negative correlation between being a *smoker* and *insurance charges*. Both upper and lower triangular formats of the correlation matrix are displayed for comprehensive insights.

## **Modeling**
The code employs various regression models for predicting insurance charges:
- *Linear Regression*
- *Support Vector Regression*
- *Polynomial Regression*
- *Decision Tree Regression*
- *Random Forest Regression*

Each model is trained, and its performance is evaluated using metrics such as *R-squared value* and *Mean Absolute Error* on both training and testing sets. The *best-performing model* is identified based on testing set metrics.

## **Conclusion**
The conclusion section summarizes the key findings of the project:
- The *Random Forest Regression model* is identified as the *best-performing model*.
- The *R-squared value* indicates a good fit.
- A sample prediction is demonstrated using user input, providing an estimated *insurance cost*.

The code provides a comprehensive workflow for predicting medical insurance prices, encompassing data exploration, feature engineering, model training, evaluation, and conclusion.
