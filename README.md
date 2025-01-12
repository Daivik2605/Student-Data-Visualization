# Student-Data-Visualization
An analysis and Visualization on the Student Data

# Student Data Visualization and Persistence Prediction

## Abstract

This project analyzes and visualizes student data to predict first-year persistence using Artificial Neural Networks (ANN). The solution includes:

- Exploratory Data Analysis (EDA)
- Data preprocessing and outlier detection
- Interactive data visualizations using Plotly, Matplotlib, and Seaborn
- A Plotly-based dashboard
- A GraphQL-powered API

The ANN model achieves an accuracy of 88% on test data, and the dashboard provides dynamic insights into student data.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Methods](#methods)
   - [Preparing Dataset](#preparing-dataset)
   - [Exploratory Data Analysis](#exploratory-data-analysis)
   - [Data Preprocessing](#data-preprocessing)
   - [Outlier Detection](#outlier-detection)
3. [Data Visualization](#data-visualization)
4. [Neural Networks Model](#artificial-neural-networks-to-predict-first-year-persistence)
5. [Dashboard](#dashboard)
6. [Results](#results)
7. [Conclusions and Future Work](#conclusions-and-future-work)
8. [References](#references)

---

## Introduction

This project focuses on student retention prediction through data analysis and visualization. We addressed missing data, categorical encodings, and outlier detection. Key insights include:

- Analysis of demographic and academic factors
- Identification of patterns in GPA, co-op participation, and funding
- Exploration of gender, age group, and residency effects on performance

---

## Methods

### Preparing Dataset

The dataset includes 1437 records and 15 columns. Preprocessing steps:

- Removed metadata rows
- Replaced "?" with `np.nan` for missing values
- Fixed data types and imputed missing values using mean/mode
- Dropped irrelevant/outlier features (e.g., High School Average Marks)

### Exploratory Data Analysis

Analyzed feature distributions, correlations, and trends:

- Strong correlations: e.g., `First Term GPA` vs `First Year Persistence`
- Visualized demographic and academic performance patterns

### Data Preprocessing

A preprocessing pipeline was developed to handle:

- Missing data
- Categorical encodings
- Data type corrections

### Outlier Detection

Used boxplots to detect and remove anomalies, e.g., GPA scores exceeding 100.

---

## Data Visualization

Key visualizations include:

- Scatterplots: Age vs GPA, First vs Second Term GPA
- Heatmaps: Feature correlations
- Bar charts: Gender and funding distribution by residency
- Pie charts: Co-op participation proportions

Dashboards offer dynamic filtering by age, residency, and gender.

---

## Artificial Neural Networks to Predict First-Year Persistence

Built a Sequential Model with:

- 2 hidden layers and ReLU activation
- Achieved 86% train and 88% test accuracy
- Predicted retention probability dynamically

---

## Dashboard

Interactive visualizations using Plotly Dash:

- Age group distribution
- Co-op participation trends
- Funding by residency
- Dynamic slicers and animation sliders for interactivity

---

## Results

We successfully:

- Built a dynamic dashboard and prediction system
- Achieved high model accuracy on test data
- Delivered actionable insights into student demographics and persistence

---

## Conclusions and Future Work

### Conclusions

The project provides:

- Insights into student performance trends
- A predictive model for first-year persistence
- A full-stack solution integrating visualizations and ANN predictions

### Future Work

- Enhance ANN model parameters for improved accuracy
- Expand dataset size for better generalization
- Explore additional visualization techniques and frontend features

---

## References

1. Plotly. (n.d.). Python: Animations. Retrieved December 13, 2024, from [https://plotly.com/python/animations/](https://plotly.com/python/animations/)

