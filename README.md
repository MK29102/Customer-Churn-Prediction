# 📉 Customer Churn Prediction

This project focuses on predicting customer churn for a telecommunications company by applying several classification algorithms, including SVM, AdaBoost, and Gradient Boosting. The workflow addresses class imbalance using SMOTE, incorporates hyperparameter tuning, and evaluates model performance through cross-validation. Some techniques and ideas were adapted from publicly available jupyter notebooks to enhance the analysis.

## 📂 Project Structure

- **churn_pred_final.ipynb** : Jupyter notebook containing the full EDA, preprocessing, SMOTE application, model tuning, and evaluation.
- **requirements.txt**: List of packages (optional)

## 🧠 Models Used

- Support Vector Machine (SVM)
- AdaBoost Classifier
- Gradient Boosting Classifier

## ⚙️ Techniques Applied

- Exploratory Data Analysis (EDA)
- Label Encoding & One-Hot Encoding
- Feature Scaling (StandardScaler)
- SMOTE for class imbalance
- Hyperparameter tuning with RandomizedSearchCV
- 5-Fold Cross-Validation

## ✅ Performance

- Best model (Tuned SVM) achieved **82% recall** on validation.
- Evaluation based on recall to handle class imbalance concerns.
