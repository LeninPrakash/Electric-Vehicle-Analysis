# Electric Vehicle Data Analysis and Machine Learning

This repository contains an exploratory data analysis (EDA) and machine learning project aimed at analyzing and predicting characteristics of electric vehicles (EVs) using a dataset of EV registrations.

## Table of Contents
- [Introduction](#introduction)
- [Overview of Dataset](#overview-of-dataset)
- [Agenda](#agenda)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning Models](#machine-learning-models)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Files](#files)
- [Usage](#usage)
- [Dependencies](#dependencies)

## Introduction
The purpose of this project is to analyze and predict characteristics of electric vehicles (EVs) using a dataset of EV registrations. The goals include understanding the distribution and types of EVs, predicting EV type based on features, and predicting the electric range of EVs.

## Overview of Dataset
The dataset used in this project contains information on electric vehicles including:
- VIN, County, City, State, Postal Code
- Model Year, Make, Model
- Electric Vehicle Type, Electric Range
- Base MSRP, Legislative District
- Vehicle Location, Electric Utility

## Agenda
1. Introduction to the Case
2. Overview of Dataset
3. EDA
   - Distribution by State, County, and City
   - Prevalence of EV Types
   - Electric Range Analysis
4. Data Preprocessing
5. Machine Learning Models
   - Predicting EV Type
   - Predicting Electric Range
6. Conclusion
7. Future Work

## Exploratory Data Analysis (EDA)
- **Distribution by State**: Analyzing the number of EVs by state.
- **Distribution by County and City**: Analyzing the number of EVs by county and city.
- **Prevalence of EV Types**: Comparing the prevalence of BEVs and PHEVs.
- **Electric Range Analysis**: Analyzing the distribution of electric ranges and comparing average ranges by make and model.

## Data Preprocessing
- Handling missing values using imputation.
- Encoding categorical variables (Make, Model).
- Scaling numerical features (Base MSRP).

## Machine Learning Models
### Predicting EV Type
- Model: Random Forest Classifier

### Predicting Electric Range
- Models: Linear Regression and Random Forest Regressor

## Conclusion
Researchers, policymakers, and industry stakeholders can use the insights from this analysis to make informed decisions regarding EV infrastructure development, incentive programs, and sustainable mobility solutions. Key insights include the importance of data preprocessing and the effectiveness of advanced models in improving prediction accuracy.

## Future Work
- Expand analysis to include more features.
- Use more advanced models and hyperparameter tuning.
- Explore the impact of geographical factors on EV adoption.
- Analyze the economic impact of EV adoption.

## Files
- `Electric_Vehicle_Analysis.ipynb`: Jupyter notebook containing the EDA and machine learning analysis.
- `Electric_Vehicle_Analysis_Presentation.pdf`: Presentation summarizing the project findings.
- `Electric_Vehicle_Analysis_Presentation_Updated.pdf`: Updated presentation with additional conclusions.
- `Electric_Vehicle_Population_Data.csv`: Dataset used for the analysis.

## Usage
To run the analysis, open the Jupyter notebook `Electric_Vehicle_Analysis.ipynb` and execute the cells. Ensure you have the dataset file `Electric_Vehicle_Population_Data.csv` in the same directory as the notebook.

## Dependencies
- pandas
- numpy
- matplotlib
- scikit-learn
- fpdf
- nbformat

Install the dependencies using pip:
```bash
pip install pandas numpy matplotlib scikit-learn fpdf nbformat
