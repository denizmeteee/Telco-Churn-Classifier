Telco Customer Churn Analysis
This project involves analyzing the Telco customer churn dataset, which contains information about customers of a telecommunications company and their decisions to either stay or leave the service. The dataset can be downloaded from Kaggle.

Project Overview
Data Visualization:

Visualized the distribution of each continuous feature.
Visualized the distribution of the target variable (churn).
Data Preparation and Splitting:

Split the data into training and test sets.
Built a pipeline for handling categorical variables.
Explored the impact of scaling continuous features using StandardScaler on the model's performance.
Baseline Model:

Developed a simple baseline model using appropriate preprocessing steps.
Performed cross-validation with a linear model to set a minimum performance benchmark.
Categorical Variable Encoding and Feature Interactions:

Experimented with different encoding techniques for categorical variables.
Investigated the effect of adding interaction terms using PolynomialFeatures on model performance.
Model Selection and Tuning:

Applied various classification models such as decision trees, random forests, gradient boosting, and SVM.
Tuned model parameters to optimize performance.
Explainable Model:

Created an explainable model with performance close to the best-performing model.
Ensured the model was simple enough to be easily interpreted (e.g., a linear model with a manageable number of coefficients or a small decision tree).
Model Evaluation:

Evaluated models using various metrics such as accuracy, precision, recall, F1-score, AUC, and AP.
Discussed how these metrics provide insights into the model's performance and identified the most relevant metrics for this problem.
Model Performance Visualization:

Visualized model results using appropriate plots such as confusion matrix, ROC curve, and precision-recall curve to gain further insights into performance.
