# Homelessness - Overview

## Introduction
The purpose of this project is to determine if homelessness can be predicted by local housing market factors. We will focus on market predictors of homelessness and Continuums of Care (CoC) to help get a sense of observations regarding both homelessness and market state in different categories.

## Requirements
Software used in this project consists of Google Colab for data preperation and analysis, and excel for the storing of data sets. 

## Data
Our data comes from The U.S. Department of Housing and Urban Development (HUD) and their report "Market Predictors of Homelessness" which can be found here: https://www.huduser.gov/portal/sites/default/files/pdf/Market-Predictors-of-Homelessness.pdf
It contains data regarding the number of homeless people, along with geographic, demographic and economic factors, which can be found in the files under the Data folder
The data for our additional step comes from https://worldpopulationreview.com/state-rankings/federal-aid-by-state and contains the amount of federal aid the government gave to each state in the year 2023.

## Data Preperation
We wanted to prepare our data for future analysis by inspecting the columns/variables given to us in our original data, checking for sufficient data for a quality analysis, scaling down number of variables, inspecting the dictionary to make sense of what the variables we're keeping are, and converting totals to rates. The code for this data preperation can be found in the Notebooks folder in the file titled "Homelessness_Data_Preparation_Hope_Crosier.ipynb"

## Data Analysis
To analyze the data for this project, we took the approach of linear regression. We wanted to find a model that would enable us to somewhat accurately predict the homelessness rate of a CoC based on predictors, and see what predictors have more significance than others. We also used lasso, ridge regression, XGBoost and cross validation methods to further analyze our models and predictions. 

## Author
Hope Crosier is the author of this repository. She is a undergraduate computer science student at Seattle University, and her linked in here: https://www.linkedin.com/in/hope-crosier/

## License
This repository and all corresponding code components are liscenced under the MIT License
