# Flight & Athlete Data: End-to-End Analysis & ML

A comprehensive data science project featuring a multi-stage pipeline: Power Query ETL, Python data refinement, and a Random Forest Machine Learning model.

## Project Overview
This repository demonstrates the ability to handle complex datasets through:
1.  **ETL Pipeline:** Transforming raw data using Power Query.
2.  **Data Cleaning:** Advanced preprocessing and renaming using Python.
3.  **Predictive Modeling:** A Machine Learning model to predict player attributes/values.

## Tech Stack
* **Data Processing:** Python (Pandas, NumPy)
* **Machine Learning:** Scikit-Learn (Random Forest Regressor)
* **Visualization:** Matplotlib, Seaborn

## Machine Learning Workflow
Using the `ML notebook.ipynb`, I implemented:
* **Feature Engineering:** Selecting key variables like `Age` and `Overall` rating.
* **Model:** Random Forest Regression to predict numerical targets.
* **Evaluation:** Calculated $R^2$ scores to ensure model accuracy.
* **Testing:** Included a custom prediction script for new data inputs.

## Repository Structure
* `players19 before cleaning.csv`: Three versions of the data (Raw, Post-PowerQuery, and Final Cleaned).
* `players19 after cleaning.csv`: Initial data wrangling and standardization.
* `ML notebook.ipynb`: Model training, evaluation, and predictions.
