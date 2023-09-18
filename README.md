# Predicting Hospital Admission at Emergency Department Triage

Data Scientist: Carol Calderon
Contact: cmcalderonr1093@gmail.com

#### Objetive 
Using machine learning, how might we predict the patient admission into the hospital in the emergency department to provide better information that helps the different stakeholders make better decisions.

#### Notebooks

###### Notebook #1: Predicting Hospital Admission at Emergency Department Triage

- Introduction
- Dataset description
- Exploratory Data Analysis
    - Data Cleaning
    - Feature exploration
    - Feature processing
- Advance Statistic Analysis

###### Notebook #2: Modeling Predicting Hospital Admission at Emergency Department Triage

- Baseline Model
    - Logistic Regression
- Class imabalance
    - Downsampling / Imbalance learn
- Feature selection
    - Variance Threshold
    - K-best
    - PCA
- Hiperparameter Optimization and Cross Validation
    - Logistic Regression
    - Decision Trees
    - Random forest
    - XGBoost
- Pipelines
    - Logistic Regression
    - Random forest
    - XGBoost
- Final Model Evaluation
    - Scores
    - Area Under the Curve
- Conclusions


#### Data resource

The dataset used in this project was originally collected and published by Hong WS, Haimovich AD, Taylor RA (2018) in their paper, 'Predicting hospital admission at emergency department triage using machine learning.' I will be using this dataset as a starting point for my own data science project, with the aim of further exploring the relationships and patterns that were observed in the original study.
Reference: Hong WS, Haimovich AD, Taylor RA (2018) Predicting hospital admission at emergency department triage using machine learning. PLoS ONE 13(7): e0201016. https://doi.org/10.1371/journal.pone.0201016


#### Enviroment

>> conda create -n er_predictor python=3.9 numpy pandas matplotlib seaborn scikit-learn=0.24.1 jupyter jupyterlab
>> conda activate er_predictor

Additional libraries:
>> conda install -c conda-forge missingno
>> conda install -c conda-forge imbalanced-learn
>> conda install -c conda-forge xgboost=1.1.1 mlxtend

Kernel:
>> ipython kernel install --name "er_predictor" --user

#### Other files

- Presentation
- Column_names: the list of variables in the original dataframe before cleaning and preprocessing