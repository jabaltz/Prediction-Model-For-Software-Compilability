# Prediction Model For Software Compilability

These codes are developed for research at [USC Center for Systems and Software Engineering (CSSE)](http://csse.usc.edu/new/).
Our group works on applying mining software repository techniques to understand the correlation of software architecture, code changes,
software quality, software evolution and technical debt in open-source software systems. The full paper will be puplished 
in proceedings of [International Symposium on Empirical Software Engineering and Measurement 2018](http://eseiw2018.wixsite.com/esem2018).

**analyze_features_compilability.ipynb**

The code is for feature engineering part. It will analyze the software repository and find out
 which characteristics can be used to distinguish uncompilable commits from compilable commits.

**prediction_model.ipynb**

The code is for prediction part. It makes prediction model based on the analysis performed by analyze_features_compilability.ipynb. It trains the logistic regression model
and performs model evaluation.

