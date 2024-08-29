
# Predictive Analytics for Heart Disease and Diabetes

The aim of this project is machine learning prediction on risk factor hypertensive patients and Diabetics heart disease, syndrom. The model process is based on the analysis of patient data regarding health records, lifestyle and environmental variables to get accurate predictions required for preventive healthcare. This project involves a lot of data visualisation, hyperparameter tuning and even an interactive web interface where you can test against your own songs!

## overview
It combines heart disease and diabetes prediction into a unified model using the Random Forest algorithm. It creates a model based on patient information, such as societal makeup and medical history of the people themselves. The goal of the project is to be able to help any research and educational effort in healthcare analytics.
## FEATURES
Dual Prediction: Predicts both heart disease and diabetes.

Data Visualization: Provides insights through correlation heatmaps, pair plots, and distribution charts.

Hyperparameter Tuning: Optimizes model performance using RandomizedSearchCV.

Interactive Web App: Built with Gradio for easy input and real-time predictions.

Easy Deployment: Can be run in Google Colab.
## Deployment

CLONE THE REPOSITORY

```bash
  https://github.com/Nil-tech/DISEASE_PREDICTION_PREDICTIVE_ANALYSIS.git
```


## Usage
Training the Model : We need to load dataset, preprocessing data and train Random Forest model given in provided jupyter notebook.

Web App: Run the web app script in your notebook or on local to open Gradio interface.

Data Input: Feed Patient Level Information through the interface of web to get predictions for Heart Disease & Diabetes.



## MODEL DETAILS
Algorithm: Random Forest

Optimal hyperparameters for RandomizedSearchCV.

Evaluation Metrics : Approach to find accuracy, Confusion Matrix, Classification Report and ROC AUC score
## DATA VISUALIZATION
Correlation Heatmap: result of correlation between features and target variables.

Pair Plots: To plot the pairwise relationships with given columns of a pandas DataFrame.

Distribution Charts: Shows the distribution of target variable.
## WEB APPLICATION
The web app is also interactive and it uses Gradio, which enables input(in form of patient features) to automatically generate predictions for the disease or diabetes. It has a neat UI and Feedback real-time.
