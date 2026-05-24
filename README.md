# Parkinson’s Disease Classification using Machine Learning

## Project Overview
This project applies supervised machine learning techniques to classify Parkinson’s disease diagnosis using demographic, clinical, and lifestyle-related patient features. Multiple machine learning models were trained, evaluated, and compared to determine the best-performing classification approach.

The project includes data preprocessing, feature selection, model training, performance evaluation, and visualization of classification results.

---

## Objectives
- Predict Parkinson’s disease diagnosis using patient-related features
- Compare multiple supervised machine learning algorithms
- Evaluate classification performance using standard metrics
- Identify the best-performing predictive model

---
## Machine Learning Models Used
The following supervised machine learning models were implemented and compared:

- Logistic Regression
- Linear Support Vector Machine (SVM)
- Radial Basis Function (RBF) SVM
- Polynomial SVM
- Random Forest Classifier
- XGBoost Classifier

---


## Best Model Performance
The Random Forest model using all features with an 80–20 train-test split achieved the best overall performance.

### Best Results
| Metric | Score |
|---|---|
| Accuracy | 0.810 |
| Precision | 0.789 |
| Recall | 0.946 |

The high recall indicates strong performance in correctly identifying Parkinson’s disease cases, which is particularly important in medical screening applications.

---
## Features Used
Example features included in the dataset:
- Age
- Gender
- BMI
- Smoking
- Alcohol Consumption
- Physical Activity
- Diet Quality
- Sleep Quality
- Family History
- Depression
- Tremor
- Rigidity
- Balance Problems
- Cognitive Decline
- Stress Levels
- Blood Pressure
- Cholesterol Levels

---


## Files
- `parkinsons_disease_classification_ml.ipynb`
- `parkinsons_disease_data.csv`
- `README.md`

---

## Requirements
Install required Python libraries:

```bash
pip install -r requirements.txt
```

Required packages:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

---
## Repository Structure
```text
├── parkinsons_disease_classification_ml.ipynb
├── parkinsons_disease_data.csv
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## Future Improvements
- Hyperparameter optimization
- Feature importance analysis
- Cross-validation
- ROC-AUC comparison
- Deep learning model experimentation

---

## License
This project is licensed under the MIT License.
