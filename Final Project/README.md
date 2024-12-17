# Final Project

## Description
The goal of this project is to create a model for telecom operator Interconnect. This models purpose will be to predict when customers are going to churn so that the company can offer them promotional codes and special plan options to persuade them to stay. To achieve this goal 4 datasets have been provided with customer information and habits with the company that will be used to train the model. The model was able to achieve company standards with a 0.85 roc_auc score. I was able to train this model on simple hyper tuning, scaling, upsampling and creating a month column to factor seasonality. Things that could improve the model further are improved hypertuning techniques with GridSearchCV, creating more relevant features, or testing other models. 

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Installation
1. Clone the repo
   
bash
   git clone https://github.com/yourusername/projectname.git
   
2. Install dependencies
   
bash
   npm install
   
## Usage
To start the application, run:
bash
npm start
Additional usage instructions here.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact Information
Your contact information or link to your GitHub profile

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
