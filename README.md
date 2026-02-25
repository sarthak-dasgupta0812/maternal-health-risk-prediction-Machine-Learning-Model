# maternal-health-risk-prediction-Machine-Learning-Model
This project develops an end-to-end machine learning pipeline for maternal health risk prediction using clinical parameters such as blood pressure, blood sugar, heart rate, and body temperature. It implements Random Forest and Dense Neural Network models, evaluates clinical performance metrics and deploys a Gradio-based web application 


#  Maternal Health Risk Prediction using Machine Learning & Deep Learning

##  Project Overview

This project presents an end-to-end clinical AI system designed to predict maternal health risk levels using routinely collected physiological parameters. The goal is to support early identification of high-risk pregnancies and enable timely medical intervention, especially in semi-urban and rural healthcare settings.

The system integrates data preprocessing, supervised machine learning, deep learning, model evaluation, and deployment into a functional clinical decision-support prototype.

---

## Objective

To build and evaluate machine learning models capable of predicting maternal health risk levels using:

- Age
- Systolic Blood Pressure
- Diastolic Blood Pressure
- Blood Sugar
- Body Temperature
- Heart Rate

Target Variable:
- **RiskLevel** (1 = High Risk, 0 = Low Risk)

---

## Dataset

The dataset is derived from rural healthcare centers in Bangladesh and originally sourced from IoT-based monitoring systems. It is publicly available via the UCI Machine Learning Repository.

The dataset contains structured clinical parameters used for binary classification of maternal health risk.

---

## Methodology

### Data Preprocessing
- Data cleaning and missing value handling
- Feature scaling using StandardScaler
- Train-test split with stratification
- Feature normalization for model stability

### Machine Learning Model
- Random Forest Classifier
- Model training and evaluation
- Feature importance analysis
- Performance metrics:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC-AUC
  - Confusion Matrix

### Deep Learning Model
- Dense Neural Network (Fully Connected)
- ReLU activation layers
- Sigmoid output for binary classification
- Binary Cross-Entropy Loss
- Adam optimizer

### Deployment
- Gradio-based web interface
- Real-time patient risk prediction
- User-friendly clinical decision support simulation

---

## Results

Both Random Forest and Neural Network models were evaluated and compared using clinical performance metrics. The system demonstrates the feasibility of AI-assisted maternal risk stratification in low-resource healthcare environments.

Feature importance analysis highlights key predictors contributing to maternal risk, supporting model interpretability.

---

## Key Learning Outcomes

- End-to-end ML workflow development
- Clinical data preprocessing strategies
- Model evaluation in healthcare contexts
- Neural network implementation
- Model deployment using Gradio
- Practical understanding of AI in maternal healthcare

---

## Ethical & Clinical Considerations

- Model bias in rural datasets
- Data quality variability
- Risk of over-reliance on automated predictions
- Importance of physician oversight
- Deployment challenges in low-resource environments

This system is intended for clinical decision support, not autonomous diagnosis.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib / Seaborn
- Gradio
- Google Colab

---

## Project Structure

