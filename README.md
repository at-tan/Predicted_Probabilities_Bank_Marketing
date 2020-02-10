# Portuguese_term_deposits
Analysis of the Portuguese bank term deposit marketing campaign

The "Campaign_I" file contains the data upload, cleaning, feature engineering and EDA.

The "Campaign_Gridsearch_SMOTE-Tomek" file has the Gridsearch of the Logistic regression, Random Forest and SVC models,
along with resampling using the combination SMOTE-Tomek algorithm.

The "Campaign_II" file shows the top All-variable Random Forest model that emerged from the Gridsearch process above.
It also analyses the explanatory variables to arrive at the top 5 variables for a more parsimonious predictive model. 
The single top variable was 'euribor3m'.

Finally, the "Campaign_III" file has the Gridsearch of Logistic regression and Random Forest using the top 5 variables.
The top 5-variable model was again Random Forest. It then analyses the precision-recall curve to pinpoint the
classification threshold at which the model's performance could be improved. The final 5-variable Random Forest model with 
changed threshold achieved performance scores on the test set that were comparable to the top All-variable model.
