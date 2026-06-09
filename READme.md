# PMOS Prediction Using Clinical and Metabolic Indicators

## Project Overview

This project investigates which clinical and metabolic indicators are most useful for predicting Polyendocrine Metabolic Ovarian Syndrome (PMOS) diagnosis using logistic regression and feature selection techniques.

The analysis focuses on identifying the strongest predictors of PMOS, evaluating model performance, and understanding why certain patients are misclassified.

## Research Question

Which clinical and metabolic indicators are most useful for predicting PMOS diagnosis, and how does model performance change when key predictors are removed?

## Dataset

The dataset contains patient-level information related to PMOS diagnosis, including:

* Age
* Body Mass Index (BMI)
* Menstrual Irregularity
* Testosterone Level
* Antral Follicle Count (AFC)
* PCOS Diagnosis

## Methods

### Exploratory Data Analysis (EDA)

* Summary statistics
* Histograms
* Boxplots
* Correlation matrix

### Predictive Modeling

* Logistic Regression
* Confusion Matrix Analysis
* Feature Importance Interpretation

### Feature Selection Experiments

* Full Model
* Model without Age
* Menstrual Irregularity Only
* BMI + Menstrual Irregularity

### Error Analysis

* False Positive Analysis
* False Negative Analysis
* Investigation of model limitations

## Key Findings

* Menstrual irregularity was the strongest predictor of PMOS diagnosis.
* BMI provided substantial additional predictive value.
* Age contributed virtually no predictive information.
* Testosterone level and antral follicle count provided smaller improvements in predictive performance.
* The full logistic regression model achieved 88.5% accuracy.
* BMI and menstrual irregularity together captured most of the predictive power of the full model.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## Future Improvements

Potential future work includes:

* Testing additional machine learning models
* Incorporating more clinical and metabolic variables
* Addressing class imbalance
* Expanding the analysis with larger datasets

## Author

Sofia Tavera

Data Analytics Student | Bentley University | 2028

