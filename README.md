## Overview
In the commercial space industry, reusing rocket stages drastically reduces costs. SpaceX's Falcon 9 first stage can be recovered and reused for future launches, saving tens of millions of dollars per mission.

# Space Y (a fictional competitor) needs to:

Predict if a first stage will be recovered based on mission parameters.
Estimate launch cost savings for competitive pricing.
Build dashboards for operational decision-making.
This project uses publicly available SpaceX launch data to train a machine learning model to predict stage landing success.

## Goals
Collect and clean SpaceX launch data from APIs and web scraping.
Perform exploratory data analysis (EDA) to identify patterns in successful landings.
Engineer features for model training.
Compare and tune multiple classification models.
Build an interactive dashboard to explore predictions.
## Project Workflow
Data Collection – API calls to SpaceX, web scraping launch records.
Data Wrangling – Cleaning, handling missing values, encoding categories.
Exploratory Data Analysis – Visualisations to understand trends and relationships.
Feature Engineering – Creating model-ready features from raw data.
Model Development – Logistic Regression, Random Forest, Gradient Boosting, etc.
Model Evaluation – Accuracy, precision, recall, F1-score, ROC-AUC.
Dashboard Creation – Plotly Dash dashboard for interactive exploration.
