# English Premier League Match Prediction

## Overview
This project analyzes English Premier League (EPL) data from 2000 to 2025 to predict match outcomes. Using various machine learning techniques, we explore patterns in historical match data and develop predictive models for match results.

## Dataset
The dataset contains EPL match information including:
- Team statistics (home/away)
- Match scores and results
- Referee information
- Season data
- Various in-game statistics (shots, corners, fouls, cards)

## Project Structure
- `notebooks/`: Jupyter notebooks for analysis
  - `1_EDA_and_Preprocessing.ipynb`: Exploratory data analysis and data preparation
  - `modeling.ipynb`: Model development and evaluation
- `Final Data -EPL_Cleaned_2000_to_2025.csv`: Main dataset

## Setup Instructions
1. Clone the repository
```bash
git clone https://github.com/[username]/RR_project.git
cd RR_project
```
2. Install dependencies
```bash
pip install -r requirements.txt
```


## Models Implemented
- Logistic Regression
- Random Forest
- XGBoost
- SHAP analysis for model interpretability


