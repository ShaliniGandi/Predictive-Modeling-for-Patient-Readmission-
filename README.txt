The main objective is to predict whether a hospitalised patient with diabetes will 
be readmitted within 30 days and the ML pipeline  generates two engineered features:
1. A patient-segment label produced by an unsupervised clustering procedure
2. A model-predicted length of hospital stay

The project includes all of the following areas:
• Exploratory data analysis and preprocessing, potentially including feature selection 
and feature engineering;
• Clustering 
• Regression;
• Classification

At each Clustering, Regression and Classification steps, Evaluated 2 suitable models and selected the final model based on the appropriate metrics.

Model Pipe Line:
The clustering model produces 'patient segment label' and Regression model produces length of stay' and Finally, The model uses the readmittance duration as a feature and performs the classification task to predict whether a hospitalised patient with diabetes will 
be readmitted within 30 days.