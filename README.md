# AdmitChanceAnalyzer

## Project Overview

**AdmitChanceAnalyzer** is a data science project aimed at predicting the likelihood of admission to graduate programs based on various applicant attributes. Using the `R` programming language, this project leverages statistical modeling and machine learning techniques to analyze and predict admission chances. The project uses a dataset containing information such as GRE scores, TOEFL scores, university ratings, GPA, letters of recommendation, statement of purpose, and research experience.

## Key Components

1. **Data Loading and Cleaning**
   - Loading the dataset and handling missing values.
   - Converting categorical variables to appropriate data types.

2. **Exploratory Data Analysis**
   - Visualizing the distribution of admission chances.
   - Analyzing the relationship between different predictors and admission chances.

3. **Model Building**
   - Splitting the data into training and testing sets.
   - Building a linear regression model to predict admission chances.
   - Evaluating the model using Root Mean Squared Error (RMSE).

4. **Feature Importance**
   - Identifying which factors most significantly impact admission chances.
   - Visualizing feature importance using bar plots.

5. **Prediction and Evaluation**
   - Making predictions on the test data.
   - Comparing predicted values with actual values.
   - Plotting actual vs. predicted admission chances for visual assessment.

## Getting Started

### Prerequisites

- R (version 4.0 or higher)
- RStudio (optional but recommended)
- Required R packages: `ggplot2`, `randomForest`, `corrplot`, `ggrepel`
