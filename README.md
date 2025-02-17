# diabetes-analysis-and-prediction

Here’s a more detailed README file for your project:

---

# Diabetes Readmission Prediction: A Decade-Long Hospital Dataset Analysis

## Overview

This project analyzes a decade-long dataset (1999-2008) from 130 U.S. hospitals and integrated delivery networks, with a focus on understanding the clinical care of diabetic patients. Specifically, we aim to examine the factors that influence early readmission of diabetic patients within 30 days post-discharge. Through careful investigation of laboratory findings, medication routines, and hospital durations, we seek to uncover patterns and trends in diabetes management within the hospital setting.

Our primary objective is to develop insights that can help guide strategies aimed at improving glycemic control, enhancing preventive and therapeutic measures, and ultimately reducing readmission rates for diabetic patients.

## Key Features

- **Dataset**: The dataset spans from 1999 to 2008 and includes information from 130 U.S. hospitals and integrated delivery networks.
- **Focus**: The analysis specifically investigates the early readmission rates of diabetic patients, exploring various factors like lab results, medication adherence, and length of stay.
- **Objective**: To identify trends that could contribute to improving diabetes management and reducing readmission rates, by using machine learning models.

## Libraries Used

This project leverages several powerful Python libraries for data analysis, machine learning, and visualization:

- **Pandas**: For data manipulation and analysis
- **Numpy**: For numerical operations
- **Matplotlib** & **Seaborn**: For data visualization and plotting
- **Scikit-learn**: For machine learning model building, preprocessing, and evaluation
- **Imbalanced-learn**: For handling imbalanced datasets through oversampling, undersampling, and SMOTE
- **CatBoost**: For gradient boosting models

### Additional Libraries:
- **PrettyTable**: For generating formatted tables
- **Scipy**: For scientific and statistical calculations
- **Warnings**: For managing warnings during runtime

## Machine Learning Models

Several machine learning algorithms are employed in this project to predict the likelihood of early readmission for diabetic patients:

- **RandomForestClassifier**: For creating a robust ensemble model that improves predictive performance.
- **GradientBoostingClassifier**: For gradient boosting techniques to improve accuracy and reduce overfitting.
- **LogisticRegression**: For logistic models that assess the likelihood of readmission.
- **DecisionTreeClassifier**: For creating interpretable decision tree models.
- **MLPClassifier (Neural Networks)**: For deep learning models.
- **KNeighborsClassifier**: For instance-based learning and classification.

## Model Evaluation

We evaluate model performance using several metrics:

- **Accuracy Score**: To measure the overall accuracy of the model.
- **ROC-AUC Score**: To evaluate the model's ability to distinguish between positive and negative classes.
- **F1-Score**: To assess the model's precision and recall balance.
- **Confusion Matrix**: For detailed classification evaluation.

## Data Preprocessing

The dataset undergoes several preprocessing steps, including:

- **Handling Missing Data**: Imputation techniques are used where applicable.
- **Feature Scaling**: Standard scaling and normalization are used to prepare the data for model training.
- **Data Imbalance Handling**: Random over-sampling, under-sampling, and SMOTE are used to address imbalanced classes.

## Installation

To run this project, ensure that the following Python packages are installed:

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn imbalanced-learn catboost
```

## How to Use

1. Clone this repository to your local machine.
2. Place your dataset in the appropriate folder or modify the path in the code.
3. Run the provided Python scripts to perform the analysis and train the models.
4. Review the generated visualizations, metrics, and predictions.


