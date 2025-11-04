# BMI Classification using Machine Learning

## 📋 Project Overview
This project focuses on predicting Body Mass Index (BMI) categories — such as Underweight, Healthy, Overweight, and Obese — based on biometric data including age, height, weight, and calculated BMI.  
The dataset used available on Kaggle:  
 [Age, Weight, Height, BMI Analysis Dataset](https://www.kaggle.com/datasets/rukenmissonnier/age-weight-height-bmi-analysis)

The main goal was to compare several machine learning models and identify which performs best for BMI classification.


## 🧮 Models Implemented
| Model | Key Parameters | Test Accuracy |
|--------|----------------|----------------|
| **Logistic Regression** | `C=1.0`, `solver='lbfgs'` | 0.89 |
| **SVM (RBF Kernel)** | `C=1.0`, `gamma='scale'` | 0.87 |
| **Random Forest** | `n_estimators=200`, `max_depth=5` | **0.98** |
| **Soft Voting Ensemble** | Combines LR, SVM, RF | 0.95 |

---

