# Comparing Outcome-Based and Learned Reward Representations in Predicting Visual Attention
**Margarita E. Nikolova | Tilburg University | 2026**


## Overview
This repository contains the analysis code for my bachelor thesis investigating 
which reward representation — immediate outcome information or learned expectation 
— better predicts visual attention during instrumental learning. The analysis uses 
cross-validated machine learning applied to trial-level eye-tracking data from 99 
participants performing a Go/NoGo task.

## Data
The data used in this project is publicly available on OSF:
https://doi.org/10.17605/OSF.IO/NSY5X

Download both CSV files and place them in the same folder as the notebook:
- eyeData_processed_35.csv
- eyeData_processed_64.csv

## Requirements
Python 3.11

Install dependencies:
pip install pandas numpy matplotlib seaborn scipy scikit-learn xgboost

## How to run
Open final2205thesisML.ipynb in Jupyter or VS Code and run all cells in order.

## Output
The notebook produces:
- AUC results table and paired t-test comparisons
- Bar chart and boxplot of AUC by feature set and model
- Impurity-based and permutation feature importance plots
- Per-participant leave-one-subject-out AUC analysis

