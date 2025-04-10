# 🛠️ Failure Prediction Using SMOTE and Random Forest

This project focuses on predicting **machine failures** using time-stamped sensor data. It leverages **SMOTE (Synthetic Minority Oversampling Technique)** to address class imbalance and a **Random Forest Classifier** for high-performing predictions.

## 📌 Project Goals
- Predict the probability of machine failure using historical sensor readings.
- Handle imbalanced data using SMOTE to improve detection of failure events.
- Train and evaluate a Random Forest model.
- Visualize performance with metrics like confusion matrix, ROC curve, and classification report.

## 🧰 Tools & Libraries
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- imbalanced-learn
- Joblib

## 📈 Highlights
- Applied SMOTE to balance minority class (`failure`)
- Achieved high recall and AUC on the test set
- Exported model and predictions for deployment or dashboard use

## 📂 Files Included
- `Failure_Classification_With_SMOTE.ipynb`: Complete training notebook
- `rf_failure_prediction_model.pkl`: Saved model
- `README.md`: Project documentation
