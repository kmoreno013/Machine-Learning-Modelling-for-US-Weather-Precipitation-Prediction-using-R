# **Machine Learning Modelling for US Weather Precipitation Prediction using R**
This project is published in the form of an R Markdown file and demonstrates the steps to develop a machine learning model to predict the amount of precipitation in a given dataset using the k-Nearest Neighbors (kNN) machine learning model.

## **Project Overview**
The goal of this project is to accurately predict precipitation levels based on historical weather data. By leveraging the kNN algorithm, the model aims to provide reliable predictions that can be used for weather forecasting and analysis.

## **Report Structure**
**I. Data Wrangling**
* Download NOAA Weather Dataset: Acquire the dataset from the NOAA repository.
* Extract and Read into Project: Load the data into the R environment.
* Select Subset of Columns: Choose relevant columns for analysis.
* Clean Up Columns: Tidy the dataset by handling missing values and inconsistencies.
* Convert Columns to Numerical Types: Ensure all necessary columns are in the correct numerical format.
* Rename Columns: Assign meaningful names to columns for better readability.
  
**II. Explanatory Data Analysis**
* Training and Testing Data: Split the data into training and testing sets to evaluate model performance.
* Analyzing Individual Feature Patterns using Visualization: Explore feature distributions and relationships using visual tools.
* Descriptive Statistical Analysis: Summarize and interpret basic statistical properties of the data.
* Basics of Grouping: Group data based on relevant features to identify patterns.
* Correlation and Causation: Analyze relationships between features to understand their impact on precipitation.
  
**III. Model Development**
* kNN Model Creation: Develop the initial kNN model using the training data.

**IV. Model Evaluation and Refinement**
* Weighted kNN Model Creation: Enhance the kNN model by incorporating weights to improve accuracy.
* Model Evaluation: Assess the model using appropriate metrics to ensure its predictive power.
  
**V. Prediction**
* Use the trained model to make predictions on new, unseen data.
  
## **Tools and Libraries**
* Programming Language: R
* Interactive Programming Tool: R Studio
* Data Manipulation: tidyverse, lubridate, tibble, purr
* Data Analysis: corrplot
* ML Model Evaluation: tidymodels, broom, Metrics, parsnip
* Data Visualization: ggplot, knitr
* Report Deployment: ShinyApps
  
## **Deployment**
The project report is deployed on ShinyApps and can be accessed via the following link:
[Machine Learning Modelling for US Weather Precipitation Prediction](https://ge6xjr-kendrick-moreno.shinyapps.io/RMD_USWeather/)
