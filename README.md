# **Credit Card Fraud Detection**

## **Overview**
This project detects fraudulent credit card transactions using machine learning. It was developed for the [Kaggle Credit Card Fraud Prediction Competition](https://www.kaggle.com/competitions/credit-card-fraud-prediction/overview).

## **Project Structure**
- `data/` → Contains training and test datasets
- `models/` → Stores trained models
- `notebooks/` → Jupyter notebooks for preprocessing, training, and evaluation


## **Training Process**
1. **Data Preprocessing**: Cleaned and balanced the dataset.
2. **Feature Engineering**: Scaled and transformed transaction features.
3. **Model Training**: Trained XGBoost, Random Forest, Logistic Regression, Anomaly Detection, and Autoencoder models.
4. **Evaluation**: Compared performance using ROC-AUC scores.

## **Key Findings**
| Model | ROC-AUC Score |
|--------|--------------|
| XGBoost | **1.000** |
| Random Forest | 0.998 |
| Logistic Regression | 0.817 |
| Anomaly Detection | 0.73 (Kaggle Public Score) |

- **XGBoost performed best**, making it the preferred model.
- **Anomaly detection struggled** compared to supervised models.
- **Feature selection & data balancing were crucial** for better fraud detection.

## **Usage & Integration**
- Deploy as a REST API for real-time fraud detection.
- Integrate with banking/payment platforms to flag suspicious transactions.
- Set up automatic alerts for fraudulent activities.

## **Improvements**
- Enhance feature engineering with user behavior analysis.
- Use hybrid models combining anomaly detection & supervised learning.
- Implement real-time adaptation for evolving fraud patterns.

## **Repository**
[GitHub Repo](https://github.com/teedonk/Fraud-Detection)

# Fraud-Detection