Capstone: Delivery Delay Prediction
Model
Random Forest Classifier (tuned via RandomizedSearchCV)
Task
Binary classification — predict whether an order will be delivered late (`is\_late`), at order-placement time
Final Metrics (test set)
F1-macro: 0.6928
ROC-AUC: 0.8313
Precision: 0.4797
Recall: 0.3877
Accuracy: 0.9196
Files
`Techtrek\_Project\_Final/` — full analysis notebook (all pipeline steps)
`data/clean\_orders.csv` — cleaned, feature-engineered dataset
`model/best\_model.pkl` — final tuned Random Forest model (joblib)
`visuals/` — key exported plots
`reports/model\_comparison.csv` — full algorithm comparison table (post-tuning)
Dataset
Brazilian E-Commerce Public Dataset by Olist (Kaggle)
