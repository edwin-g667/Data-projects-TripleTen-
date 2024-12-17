## Final Project: Solution Report
### - What steps of the plan were performed and what steps were skipped (explain why)?
- No steps of the plan were skipped all were performed in the order of the plan.
### - What difficulties did you encounter and how did you manage to solve them?
- I had trouble with ordinalencoder encoding numerical columns which I solved by converting only the numerical columns back using the original dataframes values.
- Struggled to get an adequate roc score on the final model I solved this by checking the documentation to try tuning new hyper paramters I havn't used before.
### - What were some of the key steps to solving the task?
- First I tested some basic models without hyper tuning and pick the models with the highest base scores to hyper tune. This was an important step as it would have been inefficient to hyper tune several models. Then for hyper tuning I first attempted a random search with only a handful of parameters to save on time which did not get the results I wanted. I then finally upgraded to a grid search with more extensive parameters which did meet my goals.
### - What is your final model and what quality score does it have?
- I finished testing using a CatBoostClassifier model which ended with an roc_auc score of 0.85
