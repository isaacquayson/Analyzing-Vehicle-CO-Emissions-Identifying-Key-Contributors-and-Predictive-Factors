# Analyzing-Vehicle-CO2-Emissions-Identifying-Key-Contributors-and-Predictive-Factors

## Table of Contents <br/>

### 1. Project Overview

### 2. Problem Statement

### 3. Project Objectives

### 4. Tools and Technologies Used

### 5. Data Source

### 6. Methodology
a. Data Collection<br/>
b. Data Cleaning & Preprocessing<br/>
c. Exploratory Data Analysis (EDA)<br/>
d. Feature Selection
e. Model Development
f. Model Evaluation<br/>

### 7. Insights and Findings<br/>

### 8. Conclusion<br/>


## Project Overview
This project explores vehicle carbon emissions to identify which types, classes, or attributes of vehicles contribute most to CO₂ pollution.<br/>
Leveraging a dataset of over 6,200 vehicles with attributes like engine size, fuel consumption, fuel type, and transmission, the project performs exploratory data analysis (EDA) and predictive modeling.<br/>
Visual dashboards and statistical models such as Linear Regression, Decision Tree, and Random Forest Regressors are used to understand patterns and forecast CO₂ emissions based on vehicle characteristics.<br/>

The ultimate goal is to inform both consumers and policymakers about high-emission vehicle categories and help guide efforts toward more sustainable transportation choices.


## Problem Statement
a) Identify which vehicle classes emit the highest average CO₂.<br/>

b) Understand how fuel type, engine size, and fuel consumption correlate with emissions.<br/>

c) Determine the role of vehicle attributes (e.g., make, transmission type) in predicting carbon output.<br/>

d) Develop predictive models to estimate CO₂ emissions using vehicle specifications.<br/>

e) Guide efforts toward environmental sustainability by highlighting less eco-friendly vehicle options.


## Project Objectives
a) To analyze the relationship between vehicle characteristics (such as engine size, fuel type, transmission, and class) and CO₂ emissions.<br/>

b) To identify which categories of vehicles (make, class, or fuel type) are the highest contributors to CO₂ emissions.<br/>

c) To clean and preprocess the dataset for optimal performance in analysis and machine learning tasks.<br/>

d) To perform exploratory data analysis (EDA) to uncover patterns, trends, and outliers in the dataset.<br/>

e) To build and evaluate multiple machine learning models (Linear Regression, Decision Tree, Random Forest) for predicting CO₂ emissions based on vehicle attributes.<br/>

f) To compare model performance using metrics like R² score, Mean Squared Error (MSE), and Mean Absolute Error (MAE).<br/>

g) To provide actionable insights that can support environmental policy decisions and encourage the use of low-emission vehicles.


## Tools and Technologies Used
a) Python – primary programming language for analysis and modeling<br/>

b) Pandas – data manipulation and analysis<br/>

c) NumPy – numerical computing<br/>

d) Matplotlib & Seaborn – data visualization<br/>

e) Scikit-learn – machine learning modeling and evaluation<br/>

f) Jupyter Notebook – interactive development environment<br/>

g) LabelEncoder & MinMaxScaler – data preprocessing utilities<br/>

h) Linear Regression, Decision Tree, Random Forest – regression models for prediction<br/>

i) Microsoft Excel<br/>

j) Microsoft Power BI<br/>
  1. KPI Cards: <br/>

  a. Total Vehicles: 1291<br/>

  b. Average CO₂ Emitted: 260.25 g/km<br/>

  c. Average Fuel Consumption: 9.43 L/100km<br/>

  2. Interactive Filters: <br/>

  a. Filters by Make, Vehicle Class, Fuel Type, and Transmission Type allow users to dynamically slice the data.<br/>

  3. Visual Components:

   a. Bar Chart: Average CO₂ Emissions by Vehicle Class<br/>

   b. Treemap: Distribution of vehicles by class (e.g., Compact, Subcompact, Pickup Trucks)<br/>

   c. Line Chart: Average CO₂ Emissions by Engine Size<br/>

   d. Bar Chart: Average CO₂ Emissions by Fuel Type (Ethanol, Regular Gasoline, Premium Gasoline, Diesel)<br/>

   e. Scatter Plot: Fuel Consumption (City vs Highway) showing correlation in real-world driving scenarios<br/>


## Data Source<br/>
https://www.kaggle.com/datasets/bhuviranga/co2-emissions


## Methodology
The methodology followed in this project involved several structured steps to ensure a robust and insightful analysis of CO₂ emissions data:<br/>

### 1. Data Collection<br/>

A CSV dataset containing specifications of over 6,000 vehicles, including fuel consumption, engine size, transmission type, and CO₂ emissions, was imported for analysis.<br/>

### 2. Data Cleaning & Preprocessing<br/>

a. Checked for and confirmed the absence of missing values.<br/>

b. Removed duplicate entries to ensure data integrity.<br/>

c. Converted categorical variables (e.g., Make, Model, Fuel Type) into numeric format using Label Encoding.<br/>

d. Normalized numerical features using MinMaxScaler for consistent model performance.<br/>

### 3. Exploratory Data Analysis (EDA)<br/>

a. Conducted descriptive statistics to understand data distribution.<br/>

b. Visualized relationships and distributions using bar plots, box plots, histograms, heatmaps, and scatter plots.<br/>

c. Identified high-emission vehicle categories and correlated attributes like engine size and fuel type with CO₂ output.<br/>

### 4. Feature Selection<br/>

a. Selected key features such as engine size, fuel consumption metrics, transmission, and vehicle class as predictors for CO₂ emissions.<br/>

b. Split the data into independent variables (X) and dependent variable (y).<br/>

### 5. Model Development<br/>

Applied three regression models:<br/>

a. Linear Regression – for baseline predictive performance<br/>

b. Decision Tree Regressor – to capture non-linear relationships<br/>

c. Random Forest Regressor – for enhanced accuracy using ensemble learning<br/>

d. Split data into training (80%) and testing (20%) sets for model evaluation.<br/>

### 6. Model Evaluation<br/>

a. Evaluated models using R² Score, Mean Squared Error (MSE), and Mean Absolute Error (MAE).<br/>

b. Compared performance across all three models to identify the most accurate one.<br/>

## Insights and findings
##### 1) The major factors that affect CO₂ emissions are: <br/>

a. Engine Size – strong positive correlation with CO₂ produced. <br/>

b. Cylinders – also shows a strong positive correlation with CO₂ emissions. <br/>

c. Vehicle preference trends show that most people choose SUV Small, Mid-Size, and Compact vehicles due to their eco-friendliness and lower emissions. <br/>

##### 2) The top 3 vehicle classes with the highest average CO₂ emissions are: <br/>

a. Van – Passenger <br/>

b. Van – Cargo <br/>

c. SUV – Standard <br/>

##### 3) Vehicles powered by Ethanol (E85) and Gasoline (Premium & Diesel) tend to emit higher levels of CO₂ compared to other fuel types. <br/>


## Conclusion <br/>
This project analyzed CO₂ emissions across various vehicle types using data exploration, machine learning, and Power BI visualizations.<br/>
It revealed that engine size, cylinder count, and fuel type are major contributors to emissions.<br/>
Vans and standard SUVs emit the most CO₂, while compact and mid-size cars are more eco-friendly. <br/>

Among the models tested, the Random Forest Regressor delivered the highest prediction accuracy with a 99.74% R² score.<br/>
The Power BI dashboard provided actionable insights for users to identify and choose low-emission vehicles.













