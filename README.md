# Algerian Forest Fires Prediction Project

## This project aimed to predict forest fire occurrences in Algeria using machine learning techniques. The workflow involved several key stages:

### Data Cleaning & Preprocessing:
The dataset, containing meteorological and environmental data, was cleaned to handle missing values, outliers, and inconsistencies. Features such as temperature, relative humidity, wind speed, and rainfall were standardized or normalized where necessary.

### Exploratory Data Analysis (EDA):
I conducted an in-depth analysis to identify trends, correlations, and distributions in the data. Visualizations, including scatter plots, histograms, and correlation matrices, helped uncover relationships between features and forest fires.

### Feature Engineering: 
I created new features by combining or transforming existing ones to improve model accuracy. Important meteorological factors like drought index and temperature variation were calculated to better represent the environmental conditions that influence fire risk.

### Modeling with Ridge Regression: 
Ridge Regression was employed to create a robust predictive model. Ridge regularization helped address overfitting by penalizing large coefficients, making the model more generalizable. Hyperparameters were tuned to optimize the model’s performance on the test data.

### Web Application Development (Flask):
A web application was built using Flask, allowing users to input environmental conditions and get predictions on the likelihood of forest fires. The front end was developed using HTML for easy interaction, while the back end handled the prediction logic using the trained Ridge Regression model.

### Model Evaluation: 
The model was evaluated using performance metrics like Mean Squared Error (MSE) and R-squared to ensure accuracy and reliability. Cross-validation was also used to validate the model's performance across different subsets of the data.

## Skills/Technologies Used:

Programming Languages & Libraries: Python, Pandas, NumPy
Machine Learning & Modeling: scikit-learn (sklearn), Ridge Regression
Web Development: Flask, HTML
Data Analysis: Exploratory Data Analysis (EDA), data visualization tools

