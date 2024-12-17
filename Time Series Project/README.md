# Time Series Project
# Project Description
The Sweet Lift Taxi company project aims to predict the number of taxi orders at airports for the next hour to attract more drivers during peak hours. The model developed should achieve an RMSE of no more than 48 on the test set.

Table of Contents
[Technologies and Tools Used](https://github.com/edwin-g667/Data-projects-TripleTen-/blob/main/Time%20Series%20Project/README.md#technologies-and-tools-used)
[Project Structure](#project-structure)
[Setup Instructions](#setup-instructions)
[Usage](#usage)
[Conclusion](#conclusion)

# Technologies and Tools Used
Python
Pandas
Matplotlib
Scikit-learn
NumPy
Statsmodels

# Project Structure
Data Resampling: The dataset is resampled by one hour to create a consistent timeline of taxi orders.
Data Analysis: Understanding and preparing the data to uncover patterns and insights for model training.
Model Training: Various models trained and compared, including Random Forest, Linear Regression, ARIMA, and SARIMA.
Performance Evaluation: Models evaluated based on RMSE, with SARIMA performing the best on training data with an RMSE of 28.96.

# Setup Instructions
Clone the repository to your local machine.
Ensure you have Python installed along with the required libraries. You can install missing libraries using pip:

   
   pip install pandas matplotlib scikit-learn numpy statsmodels
   

Load the dataset taxi.csv into your working directory.

# Usage
Run the script to analyze and predict taxi orders using the available models.
Evaluate model performance and choose the best one based on RMSE scores.

# Conclusion
The Random Forest and SARIMA models are robust choices for this dataset, with the SARIMA model performing best during training. However, for ease of interpretability, Random Forest was recommended despite a test RMSE of 47.76.
