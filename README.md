# Ensemble Learning: Bagging and Random Forests 

This repository demonstrates the application of ensemble learning methods to a medical diagnostic task. By utilizing Bagging and Random Forest algorithms, the project aims to reduce variance and prevent overfitting commonly associated with individual decision trees.

## Project Overview
The core objective is to predict whether a patient suffers from liver disease based on 10 clinical features, including Albumin levels, age, and gender. The project evaluates the performance gain achieved by transitioning from a single estimator to a robust ensemble of models.

##  Key Features
* **Ensemble Methods**: Implementation of **Bagging (Bootstrap Aggregating)** to create diverse subsets of the training data.
* **Medical Data Analysis**: Processing and feature engineering for the **Indian Liver Patient dataset**.
* **Classifier Evaluation**: Comparative analysis of **Decision Tree** performance versus ensemble-based **Bagging Classifiers**.
* **Hyperparameter Tuning**: Configuration of estimators and sample distribution to optimize classification accuracy.

##  Tech Stack
* **Language**: Python
* **Machine Learning**: `scikit-learn` (DecisionTreeClassifier, BaggingClassifier)
* **Data Handling**: `pandas`, `numpy`

##  Dataset Information
* **Source**: UCI Machine Learning Repository [Liver Dataset](https://www.kaggle.com/datasets/uciml/indian-liver-patient-records)
* **Source**: Kaggle [Bike Rentals](https://www.kaggle.com/competitions/bike-sharing-demand/overview)
* **Task**: Binary Classification (Predicting liver disease status)
* **Features**: 10 clinical attributes

##  Setup & Installation

### 1. Environment Configuration
It is recommended to use a virtual environment for this project:

```bash
# Create and activate the environment
git clone git clone https://github.com/Joe-Naz01/bagging_random.git
cd bagging_random

conda create -n ensemble_ml python=3.10 -y
conda activate ensemble_ml

# Install dependencies
pip install -r requirements.txt
jupyter notebook