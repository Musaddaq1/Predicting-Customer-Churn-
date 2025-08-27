# Customer Churn Prediction in Telecommunications Services

##  Project Overview
Machine learning project to predict customer churn in telecommunications services using multiple classification algorithms.

##  Objective
Predict whether a customer will leave the service (churn) based on various customer behavior and demographic features.

##  Dataset
- **Source**: E-commerce Dataset (Excel format)
- **Size**: 5,630 customers with 19 features
- **Target**: Binary classification (Churn: 0/1)
- **Class Distribution**: 83.2% Non-Churn, 16.8% Churn

##  Key Features
- **Tenure**: Customer service duration
- **PreferredLoginDevice**: Mobile/Computer
- **CityTier**: City classification
- **WarehouseToHome**: Distance metrics
- **PaymentMode**: Various payment methods
- **HourSpendOnApp**: App usage time
- **SatisfactionScore**: Customer satisfaction rating
- **OrderAmountHike**: Price increase percentage
- **CashbackAmount**: Reward amounts

##  Models Implemented
1. **Logistic Regression** - Accuracy: 81.35%
2. **Random Forest** - Accuracy: 91.30%
3. **XGBoost** - Accuracy: 94.76% ⭐

##  Key Results
- **Best Model**: XGBoost (94.76% accuracy)
- **Feature Importance**: Order-related features most predictive
- **Handling Imbalance**: SMOTE applied to training data only
- **Cross-validation**: 5-fold CV with hyperparameter tuning

##  Technologies Used
- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- SMOTE for class balancing
- GridSearchCV for optimization

##  Usage
1. Install required packages: `pip install pandas numpy scikit-learn xgboost matplotlib seaborn imbalanced-learn`
2. Run `Notebook.ipynb` for complete analysis
3. Dataset should be in `dataset/` folder

##  Performance Metrics
- **Accuracy**: Overall prediction correctness
- **Precision**: Churn prediction accuracy
- **Recall**: Churn detection rate
- **F1-Score**: Balanced precision-recall
- **AUC-ROC**: Model discrimination ability

##  Key Insights
- XGBoost outperforms other models significantly
- Order behavior patterns are strong churn indicators
- Customer satisfaction strongly correlates with retention
- Payment preferences influence churn probability

---
*Project by Musaddaq Hameed - Final Year Project*
