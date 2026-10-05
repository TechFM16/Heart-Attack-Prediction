# Heart Attack Analysis & Prediction 🧡

An exploratory data analysis and machine learning project designed to predict the likelihood of a heart attack based on clinical patient data. 

## Overview
This project processes clinical metrics (such as age, resting blood pressure, cholesterol levels, and maximum heart rate) to build, evaluate, and compare multiple predictive models. It includes extensive data visualization, outlier detection, and model tuning to identify the most accurate algorithm for determining heart disease risk.

## Machine Learning Models Evaluated
* **Logistic Regression**
* **Support Vector Machine (SVM)**
* **Stochastic Gradient Descent (SGD)**
* **Decision Tree Classification** (Includes pre-pruning techniques for variance reduction)
* **Artificial Neural Network (ANN)** (Feedforward network with dropout layers)

## Tech Stack
* **Language:** Python
* **Data Processing:** Pandas, NumPy, Scikit-learn
* **Deep Learning:** TensorFlow / Keras
* **Visualization:** Seaborn, Matplotlib

## Key Findings
* **Demographics & Risk:** Preliminary analysis indicated a higher risk concentration in specific demographics and among patients presenting with asymptomatic chest pain.
* **Clinical Indicators:** Maximum heart rate (thalach) and ST depression (oldpeak) showed strong correlations with heart attack risk.
* **Model Performance:** Model accuracies are evaluated and visualized in a comparative bar chart at the end of the pipeline, highlighting the trade-offs between standard classifiers, pruned decision trees, and neural networks.

## How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/TechFM16/Heart-Attack-Prediction.git](https://github.com/TechFM16/Heart-Attack-Prediction.git)