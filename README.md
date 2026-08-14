# 🚚 Capstone: Delivery Delay Prediction

Predicting late order deliveries at placement time using machine learning on e-commerce transaction data.

---

##  Project Overview
This project predicts whether a customer's order will experience a delivery delay (`is_late`) at the exact moment the order is placed. By identifying potential delays early, logistics managers and e-commerce platforms can proactively address supply chain bottlenecks and improve customer satisfaction.

* **Dataset:** [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) (Kaggle)
* **Task:** Binary Classification
* **Selected Model:** **Random Forest Classifier** (tuned via `RandomizedSearchCV`)

---

## 📊 Final Model Performance

Evaluated on the holdout **test set**:

| Metric | Score |
| :--- | :---: |
| **ROC-AUC** | **`0.8313`** |
| **Accuracy** | **`0.9196`** |
| **F1-Macro** | `0.6928` |
| **Precision** | `0.4797` |
| **Recall** | `0.3877` |

---

## 📂 Repository Structure

```text
├── Techtrek_Project_Final/   # Full analysis notebook containing the complete pipeline
├── data/
│   └── clean_orders.csv      # Cleaned and feature-engineered dataset
├── model/
│   └── best_model.pkl        # Serialized tuned Random Forest model (joblib)
├── reports/
│   └── model_comparison.csv  # Post-tuning evaluation across all benchmarked algorithms
└── visuals/                  # Key exported plots & feature importance charts
