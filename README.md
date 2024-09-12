# Model selection 

This project is an assignment from the **Statistical Learning** course at UC3M, focusing on machine learning and data analysis techniques. The analysis covers data preprocessing, visualization, correlation studies, and classification approaches.

## Table of Contents
- [Introduction](#introduction)
- [Data Preprocessing](#data-preprocessing)
- [Visualization](#visualization)
- [Separating Training and Test Datasets](#separating-training-and-test-datasets)
- [Study Correlation](#study-correlation)
- [Classification Approach](#classification-approach)
- [Bayes Classifiers](#bayes-classifiers)
- [Modeling](#modeling)
- [Conclusions](#conclusions)

## Introduction

This project applies statistical learning techniques to a dataset, exploring variable relationships and predicting outcomes. Key steps include:
- Data cleaning and preprocessing
- Exploratory data analysis
- Model building and evaluation using various classification techniques, including Bayes classifiers.

## Data Preprocessing

### Libraries Used:
- `tidyr`
- `dplyr`
- `mice`
- `tidyverse`
- `skimr`
- `forcats`
- `VIM`

### Steps:
1. **Check for Missing Values:** Visualized using the `aggr()` function to identify patterns.
2. **Outlier Detection:** Applied to numeric variables to handle potential outliers.
3. **Type Conversion:** Ensured proper data types for variables.

## Visualization

Data visualizations, including correlation matrices, are used to explore the relationships between variables and gain insights into the dataset.

## Classification Approach

Multiple classification models are implemented, including:
- **LDA and QDA:** Linear and Quadratic Discriminant Analysis are applied using the `MASS` library.
- **Naive Bayes Classifier:** Another model used for classification, leveraging the prior probabilities of the features.

## Model Selection

Model selection is performed to identify the best performing classifier based on cross-validation and performance metrics.

## Conclusion

The project concludes with a discussion of the results obtained from various models, their comparative performance, and insights gained from the analysis.
