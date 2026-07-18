# NASA Kepler Exoplanet Data Preprocessing & Feature Engineering

## Overview
This repository contains a robust data preprocessing and feature engineering pipeline applied to the NASA Kepler space telescope cumulative dataset. The primary objective of this project is to clean, structure and optimize raw astronomical data, preparing it for exploratory data analysis and future modeling.

## Pipeline Architecture and Technical Steps
The data wrangling process was conducted using Python and addresses real world dataset complexities.

* **Data Cleaning and Imputation:** Processed and structurally mapped a comprehensive dataset consisting of 9,564 instances, effectively handling missing numerical values through targeted median imputation strategies.
* **Feature Engineering:** Applied logarithmic transformations to specific numerical features (e.g. transit depth) to normalize skewed distributions and improve statistical reliability.
* **Dimensionality Reduction and Multicollinearity:** Conducted a rigorous correlation analysis to resolve multicollinearity issues, identifying and dropping 20 redundant error margin columns to ensure a highly optimized feature set.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Seaborn, Matplotlib
* **Environment:** Jupyter Notebook and Google Colab

## Future Work and Next Steps
The dataset is now fully cleaned and formatted. The next phase of this project involves exploring basic predictive models to analyze exoplanet candidates based on the engineered feature set.

## Data Source
The raw dataset used in this project is publicly available and was obtained from the Kepler Exoplanet Search Results on Kaggle.
