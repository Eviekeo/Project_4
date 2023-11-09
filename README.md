# Insurance - Claim Processing Durations

## Purpose
The purpose of this project was to create a website where users could input certain variables (distribution channel and insurance cover type), which would then provide the user with a list of insurance providers in order of which provider could process a claim more efficiently. 

The goal was to assist users in their search for the best insurer to obtain cover from.

## Data processing
Data was obtained from APRA and cleaned using python and jupyter notebook.
- Target variable: `Value`
- Feature variables: `Company Name`, `Channel Type` and `Cover Type` 


## Compiling, Training, and Evaluating the Model
Four regression models were used and assessed
1. linear regression
2. random forest regression
3. decision tree regression
4. knn regression

Random forest regression was assessed to be the best model, as it had the lowest mean squared error and highest R-squared score:

