## Credit-Risk Modelling

I undertook this project to improve my classification skills and also to deal with imbalanced data. I wanted to further my knowledge in applying techniques such as hyperparamter tuning, SMOTE and cross-validation into my ML-models. I study finance and risk is a significant role in many of my modules and a project like this offers insights into Data Science technqiues that may be used in the finance industry.

This project really showed me the effect of applying hyperparameter tuning and conducting model comparisons can have on end-results. Given that this is a project I am publishing, this was the first time where I used more than 2 models for comparison and employed many techniques to get the best results possible and althought this does use pre-existing data and is nothing ground-breaking, being able to model these situations is highly valuable.

Results Summary:
1. XGBoost was the top performer among the models I chose achieving a mean ROC-AUC score of **0.88** and a mean Accuracy score of **0.8** showing fantastic end-results.
2. Results like accuracy fell but only by a minimal amount  but this lead to the F1-score and other metrics seeing significant improvements resulting in an overall robustness of the XGBoost model
3. RandomForest also performed very well but its ROC-AUC was moderately lower compared to XGBoost and other performance metrics were lower as well.
