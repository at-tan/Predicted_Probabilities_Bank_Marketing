# Tackling Imbalanced Data with Predicted Probabilities
Predicted probabilities from classification algorithms provide a key tuning mechanism to help boost their predictive power, especially in cases of imbalanced data. However, the predicted probabilities need to be calibrated before they may be used to indicate the optimal probability threshold to maximise the scoring metric of choice.

The article discusses some key scoring metrics for imbalanced data. It then explores the differences in predicted probabilities across five machine learning algorithms, namely Logistic Regression, Naive Bayes, Random Forest, Support Vector Classification and XG Boost. It finally demonstrates how predicted probabilities may be used to improve these models' performance in a case study. The data is adapted from the 2014 Portuguese bank marketing dataset, where the target variable is successful subscriptions to a term deposit. The probability of picking a "yes" in the target variable is just 11.27%.

These files contain the data and Python code used for the article published in: https://medium.com/data-science/tackling-imbalanced-data-with-predicted-probabilities-3293602f0f2
