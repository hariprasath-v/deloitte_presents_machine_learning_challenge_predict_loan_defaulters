# deloitte_presents_machine_learning_challenge_predict_loan_defaulters

### Competition hosted on <a href="https://machinehack.com/hackathon/deloitte_presents_machine_learning_challenge_predict_loan_defaulters/overview"> MACHINEHACK </a>

# About

### Build a machine learning model that predicts the loan defaulter.


#### Initially tried the ensemble models(catboost,xgboost,lightgbm).All the ensemble model's logloss values didn't show any difference. So i have tried neural network model and it gives smaller logloss value than the ensemble models and better leaderboard rank.

### Competition Public LB Rank: 146/465   & Private LB Rank: 146/465

### Final Score 0.3782

### Evaluation Metric is Logloss.

### File information

 * deloitte_ml_challenge_predict_loan_defaulters.ipynb
    ### Packages Used,
        * Sklearn
        * catboost
        * xgboost
        * lgbm
        * keras
        * Pandas
        * klib
        * Numpy
        * Matplotlib
        * Optuna
        * shap
        
     ### Basic Exploratory Data Analysis
     ### Created Catboost classifier model and tune the hyperparameters with the optuna framework.
     ### Created XGboost classifier model and tune the hyperparameters with the optuna framework.
     ### Created Lightgbm classifier model and tune the hyperparameters with the optuna framework.
     ### Model interpretation with shap  
     ### Created keras neural net model
     ### Model Comparison
     


### Feature Importance Catboost  

![Alt text](https://github.com/hariprasath-v/deloitte_presents_machine_learning_challenge_predict_loan_defaulters/blob/main/Catboost_Feature_Importance_Plot.png)


### Feature Importance XGboost  

![Alt text](https://github.com/hariprasath-v/deloitte_presents_machine_learning_challenge_predict_loan_defaulters/blob/main/XGBoost_Feature_Importance_Plot.png)


### Feature Importance Lightgbm  

![Alt text](https://github.com/hariprasath-v/deloitte_presents_machine_learning_challenge_predict_loan_defaulters/blob/main/LGBM_Feature_Importance_Plot.png)


### Model's Validation Logloss comparison

![Alt text](https://github.com/hariprasath-v/deloitte_presents_machine_learning_challenge_predict_loan_defaulters/blob/main/Model's_Validation-Logloss_Comparison.png)

