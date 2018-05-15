# Prediction Model For Software Compilability
By Patavee Meemeng

These codes are developed for research at [USC Center for Systems and Software Engineering (CSSE)](http://csse.usc.edu/new/).

Our research group works on applying mining software repository techniques to understand the correlation of software architecture/code changes,
software quality, software evolution and technical debt in open-source software systems.

These codes perform source code analysis in term of [software compilability](https://ieeexplore.ieee.org/document/8009930/). 
We analyze the repository of open-source software systems and make a prediction model to
predict whether commits will break the compilability of the software (called uncompilable commits). 

**analyze_features_compilability.ipynb**

The code will analyze the software repository and find out which characteristics can be used to distinguish uncompilable commits from compilable commits.

**prediction_model.ipynb**

The code will implement prediction model based on the analysis performed by analyze_features_compilability.ipynb. It trains the logistic regression model
and performs model evaluation.






