# Forest-Cover-Type-Classification

A machine learning system that predicts forest cover types (7 classes) from cartographic and environmental data using **Random Forest** and **XGBoost**.

## Dataset

[UCI Covertype Dataset](https://archive.ics.uci.edu/ml/datasets/Covertype)

## Key Steps
1. Data loading (581,012 samples with 54 features)
2. Feature standardization (numerical features only)
3. Data splitting (80% train, 20% test)
4. Model training (Random Forest vs XGBoost)
5. Performance evaluation

## Training
Models: Random Forest & XGBoost
Objective: Multi-class classification
Metrics: Accuracy, Precision, Recall
Validation: 20% holdout set

## Class Distribution
<img width="876" height="547" alt="Class Distribution" src="https://github.com/user-attachments/assets/e8e59160-806a-42e6-8b62-b338becf46c1" />

## Results
### Random Forest
<img width="524" height="455" alt="RF_confusion_matrix" src="https://github.com/user-attachments/assets/25be2c5e-f8f7-4245-9cd2-a7d7c615764b" />


### XGBoost
<img width="524" height="455" alt="XGB_confusion_matrix" src="https://github.com/user-attachments/assets/4921f378-67c6-41fd-8f61-2af8e617dffa" />

## Most Important Features
### Random Forest
<img width="776" height="435" alt="RF_important_features" src="https://github.com/user-attachments/assets/9818b9cd-676e-457c-94dd-fdfd3c822aa6" />

### XGBoost
<img width="656" height="435" alt="XGB_important_features" src="https://github.com/user-attachments/assets/39fc4d6c-8d91-4482-890d-3525a5d722c2" />

## Requirements

Python 3.12

pandas

xgboost

scikit-learn

matplotlib

seaborn
