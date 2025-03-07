# House Price Prediction Model

## Overview

This project develops a machine learning model capable of predicting house prices with significant accuracy. It caters to real estate and finance professionals, empowering buyers, sellers, and investors with informed decision-making. The model is built using curated data and leverages the power of machine learning algorithms implemented with popular Python libraries like Scikit-learn and XGBoost. By analyzing features such as square footage, number of bedrooms, and location data, the model achieves a Mean Squared Error (MSE) of less than 100,000 on the test set, offering a powerful tool for accurate house price estimations.

## Model Architecture

**Data Collection and Processing:** The project utilizes the "California Housing" dataset, which can be directly downloaded from the Scikit-learn library. The dataset contains features such as house age, number of rooms, population, and median income. Using Pandas, the data is processed and transformed to ensure it is suitable for analysis.

**Data Visualization:** The project employs data visualization techniques to gain insights into the dataset. Matplotlib and Seaborn are utilized to create visualizations such as histograms, scatter plots, and correlation matrices. These visualizations provide a deeper understanding of the relationships between features and help identify trends and patterns.

**Train-Test Split:** To evaluate the performance of the regression model, the project employs the train-test split technique. The dataset is split into training and testing subsets, ensuring that the model is trained on a portion of the data and evaluated on unseen data. This allows for an accurate assessment of the model's predictive capabilities.

**Regression Model using XGBoost:** The project utilizes the XGBoost algorithm, a popular gradient boosting framework, to build the regression model. XGBoost is known for its ability to handle complex relationships between features and achieve high predictive accuracy. The Scikit-learn library provides an implementation of XGBoost that is utilized in this project.

**Model Evaluation:** The project assesses the performance of the regression model using evaluation metrics such as R-squared error and mean absolute error. R-squared error measures the proportion of the variance in the target variable that can be explained by the model, while mean absolute error quantifies the average difference between the predicted and actual house prices. These metrics provide insights into the model's accuracy and precision. Additionally, a scatter plot is created to visualize the predicted prices against the actual prices.




