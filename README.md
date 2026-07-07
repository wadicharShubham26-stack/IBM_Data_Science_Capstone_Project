# IBM_Data_Science_Capstone_Project
## Overview

This project is part of the IBM Applied Data Science Capstone and focuses on predicting whether the SpaceX Falcon 9 first-stage booster will successfully land after launch. SpaceX has significantly reduced launch costs by reusing its rocket boosters, allowing it to offer launches at a much lower price than many competitors. By building a machine learning model to predict landing success, this project demonstrates how data science can be used to estimate mission outcomes and support cost analysis for organizations competing in the commercial space industry.

## Project Objectives

The project follows a complete end-to-end data science workflow, covering data collection, preprocessing, exploratory analysis, visualization, database querying, and predictive modeling.

1. Data Collection and Preparation
Retrieved Falcon 9 launch data from the SpaceX REST API.
Cleaned and transformed the dataset by handling missing values and ensuring consistent formatting.
Prepared the data for analysis and machine learning.
2. Web Scraping Launch Records
Extracted additional Falcon 9 launch information from Wikipedia using BeautifulSoup.
Parsed HTML tables and converted them into structured Pandas DataFrames.
Combined scraped data with API data for a richer dataset.
3. Exploratory Data Analysis (EDA)
Explored launch trends using Pandas, Matplotlib, and Seaborn.
Identified relationships between launch characteristics and landing success.
Created training labels for predictive modeling.
4. SQL Database Analysis
Loaded the cleaned dataset into an IBM Db2 database.
Executed SQL queries to analyze launch records and extract business insights.
5. Feature Engineering and Geospatial Visualization
Engineered additional features to improve model performance.
Created interactive maps using Folium to visualize launch sites and landing outcomes.
Examined geographic patterns influencing mission success.
6. Interactive Dashboard Development
Built an interactive dashboard using Plotly Dash.
Added dropdown menus and range sliders for dynamic filtering.
Enabled users to explore launch statistics through interactive charts and visualizations.
7. Machine Learning Modeling
Standardized the dataset and divided it into training and testing sets.
Trained multiple classification models, including:
Logistic Regression
Support Vector Machine (SVM)
Decision Tree Classifier
K-Nearest Neighbors (KNN)
Applied GridSearchCV to optimize model hyperparameters.
Compared model performance using test accuracy.

## Results

Model	Test Accuracy
Decision Tree Classifier	94.44%,
Support Vector Machine (SVM)	83.33%,
K-Nearest Neighbors (KNN)	83.33%.

The Decision Tree Classifier achieved the highest test accuracy, making it the most effective model for predicting Falcon 9 first-stage landing success.

## Conclusion

This capstone project demonstrates a complete data science pipeline, from collecting raw data to deploying predictive machine learning models. By combining API data, web scraping, SQL analysis, interactive visualizations, and supervised learning techniques, the project successfully predicts Falcon 9 landing outcomes. The workflow highlights practical applications of data science in aerospace analytics and provides insights that can assist in evaluating launch costs and mission success probabilities.
