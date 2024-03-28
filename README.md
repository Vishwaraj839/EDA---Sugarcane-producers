# EDA---Sugarcane-producers


# Sugarcane Production Analysis

This repository contains a Jupyter Notebook that performs an analysis of sugarcane production data using Python and popular data analysis libraries such as Pandas, Seaborn, and Matplotlib.



## Dataset

The dataset contains information about sugarcane production in various countries. It includes the following columns:

- `Country`: The name of the country.
- `Continent`: The continent where the country is located.
- `Production(Tons)`: Total sugarcane production in tons.
- `Production_per_person(Kg)`: Sugarcane production per person in kilograms.
- `Acreage(Hectare)`: Total acreage of land used for sugarcane cultivation in hectares.
- `Yield(Kg/Hectare)`: Yield of sugarcane in kilograms per hectare.

## Data Cleaning

The initial data cleaning steps include removing unwanted characters (e.g., commas, dots) from numeric columns and dropping irrelevant columns. The future warnings during data cleaning are acknowledged but not significant to the analysis.

## Univariate Analysis

The univariate analysis examines individual columns separately. It includes visualizations such as bar plots and distribution plots to understand the data distribution and identify outliers.

## Bivariate Analysis

The bivariate analysis explores the relationships between two variables, such as land area vs. total production and yield per hectare vs. total production. Scatterplots and bar plots are used to visualize these relationships.

## Correlation Analysis

The correlation analysis investigates the relationships between numerical variables. A heatmap is used to visualize the correlation matrix and identify any significant correlations.

## Analysis by Continent

The analysis is also conducted at the continent level to understand how production and other variables vary across different continents. Bar plots and line plots are used to visualize these comparisons.


