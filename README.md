# ODS_Alice
Competition "Alice" - user identification on the Internet by a sequence of transitions through sites.


## Formulation of the problem
For each session using Logistic Regression model, you need to predict whether the session belongs to Alice (label "1") or not (label "0").

## Decision Evaluation Metric
The target metric is ROC AUC.

## Results 
Best score on hidden data is 0,958974 with features:
* sites and domens (using TF-IDF)
* day of week
* part of day
* mean time of session
* num not null sites
* favorite day
* time difference between sessions
