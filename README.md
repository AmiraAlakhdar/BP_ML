This code was used to analyse the blood pressure data for the project titled:
# Project: Predicting Post-TEVAR Outcomes Using BP Metrics and Aortic Geometry

## Summary
Hypertension is a well-known risk factor for the propagation of type B aortic dissections; however, limited data exists on its impact following surgical repair. While metrics such as BP variability have been associated with higher risk of cardiovascular events, these metrics have not been explored post-TEVAR, where management has largely focused on reducing systolic BP. By pairing unique BP metrics with preoperative aortic geometry—shown to predict post-TEVAR outcomes—we can better understand which BP metrics are most useful.

This project uses BP data collected in the first 24 hours after TEVAR for a cohort of 31 patients to calculate 24 unique BP metrics, including measures of centrality, variability, and stationarity. Preoperative CTA imaging data were used to create surface models for each aorta, defining aortic geometry as a unique point in the validated shape-size feature space. Logistic regression models using these BP and aortic geometry metrics were created to predict successful TEVAR outcomes, following standard feature selection procedures, and were validated using cross-validation (CV). Training and CV accuracy were compared between the models to determine the most generalizable model.
