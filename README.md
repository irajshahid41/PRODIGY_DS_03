# PRODIGY_DS_03

## Overview

I performed an **Exploratory Data Analysis (EDA)** on the **Bank Marketing** dataset. The dataset contains information related to a bank's marketing campaigns, with the goal of predicting whether a client will subscribe to a term deposit (labeled as "deposit").

## Key Steps

1. **Data Loading and Initial Exploration**
     - Loaded the dataset using pandas and renamed the target column from 'y' to 'deposit'.
     - Examined the dataset's structure, including its shape, columns, and data types.

2. **Data Cleaning**
     - Checked for duplicates and missing values (none found).
     - Separated columns into categorical and numerical features for further analysis.

3. **Descriptive Statistics**
     - Generated summary statistics for numerical and categorical columns.
     - Identified key insights, such as the distribution of client ages, job types, and education levels.

4. **Data Visualization**
     - Created visualizations to explore relationships between features and the target variable ("deposit").
     - Analyzed correlations between numerical features to identify potential patterns.

5. **Key Findings**
     - **Imbalanced Target Variable:** The dataset is imbalanced, with significantly more "no" responses than "yes" for the deposit subscription.

     - **Feature Insights:**

          - Most clients are married and hold a university degree.
          - The majority of clients were contacted via cellular calls.
          - The "duration" of the last contact shows a strong correlation with the target variable.

6. **Next Steps**
     - **Feature Engineering:** Create new features or transform existing ones to improve model performance.
     - **Model Building:** Use classification algorithms (e.g., logistic regression, random forest) to predict deposit subscriptions.
     - **Handling Imbalance:** Address the class imbalance using techniques like SMOTE or class weighting.

## Conclusion

This EDA on the **Bank Marketing Dataset** revealed key insights into client behavior, including demographic trends and campaign effectiveness. The dataset is **imbalanced**, with most clients declining term deposits. **Duration of contact** and **communication method** significantly influence subscription rates.

📊 Dataset Source: **UCI Machine Learning Repository**[https://archive.ics.uci.edu/ml/datasets/Bank+Marketing]

For detailed code and analysis, refer to the Task03.ipynb file.

## Repository Structure

**Task03.ipynb:** Jupyter notebook containing the full EDA.

**bank+marketing.csv:** Dataset used for analysis.

## How to Use
- Clone the repository.
- Open Task03.ipynb in Jupyter Notebook or Google Colab.
- Run the cells to reproduce the analysis.
