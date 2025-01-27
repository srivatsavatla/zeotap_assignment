# Data Science Assignment: eCommerce Transactions Dataset

## Overview

This repository contains the solutions for the **Data Science Assignment** based on an eCommerce Transactions dataset. 
The goal of the assignment was to perform exploratory data analysis (EDA), build predictive models, and derive actionable insights. The assignment is divided into three main tasks, which are:

1. Exploratory Data Analysis (EDA) and Business Insights.
2. Building a Lookalike Model to recommend similar customers based on transaction history and profile.
3. Customer Segmentation using clustering techniques to group customers based on their behavior.

## Tasks Completed

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
In this task, I have performed EDA on the provided dataset, visualized various trends, and extracted business insights. The following major insights were derived from the data:

- **Insight 1**: The Majority of the customers are from the South America region region comprising of 29.5% of the userbase.
- **Insight 2**: The majority of the transactions are in the month of January. The least number of transactions are in the month of November.
- **Insight 3**: The average price spent in a month is greatest in the month of April with an average amount of $290.46 and least in the month of March with an average price of $224.60.

  
Rest of the insights are written in more detail in the report *Srivatsav_Atla_EDA.pdf* and the corresponding code is available in the *Srivatsav_Atla_EDA.ipynb* file


### Task 2: Lookalike Model
For this task, I developed a Lookalike Model that recommends the top 3 most similar customers based on their profile and transaction history. 
The model used both customer demographic information and transaction data to calculate similarity scores.

The correspondinf code is present in *Srivatsav_Atla_Lookalike.pdf* and the scores are present in the *Srivatsav_Atla_Lookalike.csv* file

### Task 3: Customer Segmentation / Clustering
For this task, I used clustering techniques to segment customers based on their profile and transaction history. 
I applied the KMeans algorithm and evaluated the model using the DB Index to assess clustering quality. Visualizations were created to display the clusters.

The detalied report with the visualization is present in the *Srivatsav_Atla_Clustering.pdf* and the corresponding code is present in the *Srivatsav_Atla_Clustering.ipynb* filee

## Repository Structure

```plaintext
├── Srivatsav_Atla_EDA.ipynb                         # Jupyter notebook for Exploratory Data Analysis
├── Srivatsav_Atla_EDA.pdf                    # PDF report with business insights
├── Srivatsav_Atla_Lookalike.ipynb             # Jupyter notebook explaining the Lookalike Model
├── Srivatsav_Atla_Lookalike.csv                     # File containing the top 3 lookalike customers with similarity scores
├── Srivatsav_Atla_Clustering.ipynb           # Jupyter notebook with clustering code and visualizations
├── Srivatsav_Atla_Clustering.pdf            # PDF report with clustering analysis and results
├── README.md                        # This README file
