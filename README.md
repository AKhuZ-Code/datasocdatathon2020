# DatasocDatathon2020

Project: UNSW DataSoc x Atlassian Datathon 2020 - Linear Regression Model

Date: 04/10/2020

## Built with...

• Python (os, pandas, pyplot (matplotlib), numpy, seaborn)

## File Dictionary

• <b>datathon.py:</b> Python code file for data preprocessing, model implementation, and model testing

• <b>combined_time_series.csv:</b> A dataset containing all given time-series data merged together

• <b>Correlation bar chat.png:</b> Correlation between predictors and the response (future number of cases)

• <b>Correlation heatmap.png:</b> Correlation between all predictors used in the model

## Motivation 

Problem Statement:

<b>"How have countries’ characteristics
(social, cultural, economic, and political values and indicators) impacted their response to COVID-19 and its effectiveness?"</b>

  • We were given a dataset on the government responses for each country against COVID-19 over time, and core datasets on number of cases/deaths/recoveries for each country over time (+ other datasets)
  
  • I wanted to examine the effectiveness of specific government responses towards COVID-19
  
## Summary of Code
  
  • Performed feature engineering on variables in the dataset and created various visualisations to examine correlations
  
  • Programmed and implemented a Linear Regression Model that would predict the future number of cases/deaths/recoveries using various predictors including: government responses taken, current number of cases/deaths/recoveries
  
  • Also made use of other models (Ridge and Lasso) to compare accuracies
  
  • The columns for number of cases/deaths/recoveries were normalised using the population of each country
  
## Summary of Results
  • Overall, the R-squared for the model ranged between 0.25-0.3, and so it wasn't worthwhile incorporating it in our analysis
  
  • We have a range for our R-squared as we tested the model with three different response variables (without changing the predictors): future cases, future deaths, future recoveries
