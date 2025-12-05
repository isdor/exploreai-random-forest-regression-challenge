# ExploreAI Random Forest Regression Challenge

This repository contains the solution and workings for the ExploreAI Academy code challenge on Random Forest Regression. The challenge focuses on building a predictive model for world population using the Random Forest Regression ensemble method.

## Project Overview

The goal of this challenge is to:
1.  **Prepare Data**: Organize world population data for a given income group into a suitable format for machine learning.
2.  **Split Data**: Implement k-fold cross-validation to create training and testing splits.
3.  **Train Model**: Train multiple `RandomForestRegressor` models across different data splits.
4.  **Select Best Model**: Identify and return the best-performing model based on the highest mean squared error on the test sets.

## Data

The project uses two datasets:
*   `world_population.csv`: Contains historical population data for various countries from 1960 to 2017.
*   `metadata.csv`: Provides metadata about countries, including their income groups.

## Technologies Used

*   Python
*   Pandas (for data manipulation)
*   NumPy (for numerical operations)
*   Scikit-learn (for `RandomForestRegressor` and `KFold`)

## How to Use

1.  Clone this repository:
    ```bash
    git clone https://github.com/YourUsername/exploreai-random-forest-regression-challenge.git
    ```
2.  Open the `.ipynb` file in Google Colab or Jupyter Notebook.
3.  Run the cells sequentially to see the data loading, preprocessing, model training, and evaluation steps.

## Setup and Installation

No specific installation steps beyond a standard Python environment with `pandas`, `numpy`, and `scikit-learn` are required. If using Google Colab, these libraries are typically pre-installed.
