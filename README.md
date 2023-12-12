This report presents a project focused on predicting the age of Parkinson's Disease onset based on speech and motor pattern measurements. 
Utilizing a dataset from Kaggle, sourced from a study analyzing speech biomarkers in patients with rapid eye movement sleep behavior disorder 
(RBD), the project aims to enhance screening and diagnostic procedures for PD. Exploratory data analysis examines patient distributions, 
antidepressant medication usage, and speech patterns, revealing correlations between family history and speech pauses. Machine learning models 
are evaluated, with the XGBoost Regressor emerging as the most accurate, achieving a mean squared error of 5.28. The top 10 features influencing 
predictions include current medications, family history, and gender. The report suggests that, while the model demonstrates some accuracy, 
further improvements hinge on expanding the dataset and refining feature selection, especially focusing on speech pattern features.

Packages used:
Python 3.11.4
Pandas version: 2.0.3
Numpy version: 1.24.4
Seaborn version: 0.12.2
Matplotlib version: 3.7.2
Scikit-learn version: 1.3.0
Scipy version: 1.11.2
XGBoost version: 1.7.6
