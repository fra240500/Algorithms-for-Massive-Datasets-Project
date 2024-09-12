# Algorithms for Massive Datasets Project

## Description
This project involves a Market Basket Analysis performed on a dataset of LinkedIn skills and job titles. The analysis was done using PySpark on Google Colab, and two key algorithms were implemented:
- Apriori, applied for frequent itemset mining with a bottom-up approach.
- FP-Growth, an optimized method to extract frequent patterns efficiently using an FP-tree.

## Repository Contents
The repository contains the following files:

- **AMD_project.ipynb**: The colab notebook containing the code and analysis.
- **MBA_project_report.pdf**: The final report explaining the methodology, results, and conclusions.

## Dataset
The dataset consists of job titles and associated skills (Source: [Kaggle](https://www.kaggle.com/datasets/asaniczka/1-3m-linkedin-jobs-and-skills-2024)). It can be downloaded by running the notebook code using your Kaggle API credentials.

## Requirements
To run the notebook and reproduce the project results, the following requirements are needed:

- Python (Google Colab notebook or Jupyter Notebook), with this libraries: pyspark, pandas, matplotlib, numpy, itertools.
