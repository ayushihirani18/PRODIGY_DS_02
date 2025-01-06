# Titanic Dataset Analysis - Prodigy Internship Task 2

This repository contains the code and analysis performed for Task 2 of my Prodigy Internship. The goal of this task was to analyze the Titanic dataset, perform data cleaning, and conduct exploratory data analysis (EDA) to uncover meaningful insights.

## Overview

The Titanic dataset provides information on the passengers aboard the Titanic, including demographic details, ticket information, and survival status. This analysis explores trends, correlations, and key factors influencing survival rates.

## Key Features

- **Data Cleaning**: 
  - Handled missing values in columns like `Age` and `Embarked`.
  - Dropped columns with excessive missing data (e.g., `Cabin`).
  - Optimized data types for memory efficiency.
  
- **Feature Engineering**:
  - Created a new `FamilySize` feature by combining `SibSp` and `Parch`.
  
- **Exploratory Data Analysis (EDA)**:
  - Visualized survival rates based on gender, age, passenger class, and embarkation points using Seaborn and Matplotlib.
  - Analyzed the distribution of features like age and fare.

## Usage

- **Dataset**: Ensure that the Titanic dataset (`train.csv`) is in the working directory.
- **Visualization**: Generate insightful plots by running the code.
- **Insights**: Use the analysis to understand factors impacting survival rates.

## Results

Key observations from the analysis:
- Women had higher survival rates than men.
- Passengers in first class were more likely to survive compared to those in second and third class.
- Younger passengers had slightly higher survival rates.

## Tools and Libraries Used

- Python
- Pandas
- Seaborn
- Matplotlib

DATASET:https://www.kaggle.com/c/titanic/data
## Acknowledgments

- [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)
- Prodigy Internship Team for their guidance and support.

Feel free to contribute or share feedback to improve the project!
