---
title: Exploration of Heart Rate Variability for the Prediction of Performance in Youth Footballers"
collection: publications
permalink: /publication_publications/2024-09-11-Exploration-of-HRV-for-Prediction-of-Performance
excerpt: 'The study was to explore prediction quality of resting short-term heart rate variability (HRV) parameters with endurance performance in youth footballers.'
date: 2024-09-11
venue: 'Computing in Cardiology conference'
paperurl: 'https://cinc.org/2024/Program/accepted/136.pdf'
citation: 'Korzeniewski, K., Gąsior, J., Mikielewicz, M., Rosol, M., Makucha, R., Mlynczak, M., (2024). Exploration of Heart Rate Variability for the Prediction of Performance in Youth Footballers. 2024 Computing in Cardiology (CinC), Karlsruhe, Germany, 2024-09.'
---
**Authors:**
**Kacper Korzeniewski**, Jakub S. Gąsior, Magdalena Mikielewicz, Maciej Rosoł, Robert Makuch and Marcel Młyńczak


**Abstract:**

&nbsp;&nbsp;&nbsp;&nbsp;**Aims:** The study was to explore prediction quality of resting short-term heart rate variability (HRV) parameters with endurance performance in youth footballers.

&nbsp;&nbsp;&nbsp;&nbsp;**Methods:** Male players (n=222) with mean age of 13±2.3 years underwent short-term (5-minute) RR intervals (RRi) measurement in supine position using heart rate monitor (Polar Team2). Stationarity of RRi was assessed using the Augmented Dickey-Fuller test (a=0.05). Time-domain and nonlinear HRV parameters were calculated. The data split as 75:25 for training and testing, respectively and standardized. Gradient Boosting (GBR), AdaBoost (ABR), and Random Forest (RFR) regressors were utilized to estimate endurance performance: VO2max from Yo-Yo Intermittent Recovery Test Level 2. The best parameters were chosen via 10-fold cross-validation on the training set. Then, the models were taught on the full training dataset and validated on the test set with the mean absolute error (MAE) and root mean square error (RMSE). Key HRV parameters were determined using explainable artificial intelligence (XAI) tools, then rankings were created for the most significant features with a score ranging from 1 to 5 for each model (5 as the most significant).

&nbsp;&nbsp;&nbsp;&nbsp;**Results:** 78% of RRi were stationary. The best setting for GBR model were: learning rate (lr):0.1, max depth:6, estimators (ne):100. Performance metrics of the model on the test data were: MAE:4.2, RMSE:5.1. The best setting for ABR model were: lr:0.01, loss: square, ne:225 Performance metrics of the model on the test data were: MAE:3.7, RMSE:4.4. The best setting for RFR model were: criterion: absolute error, ne:125. Performance metrics of the model on the test data were: MAE:3.8, RMSE:4.6. The most important features were presented
in table.

&nbsp;&nbsp;&nbsp;&nbsp;**Conclusion:** This study utilized machine learning methods to identify key HRV parameters associated with youth footballers endurance performance. Significant parameters, mean RRi, DFAα2, and SD1/SD2, appeared to be the most important in predicting endurance performance outcome.





