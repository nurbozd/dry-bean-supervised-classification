# Dry Bean Supervised Classification

This project applies supervised machine learning methods to classify dry bean types using physical and geometric measurements from the Dry Bean Dataset.

The project focuses on building and evaluating classification models for automated bean type prediction.

---

## Project Aim

The main goals of this project are:

- classify dry bean types automatically,
- compare Decision Tree and Random Forest models,
- optimize model hyperparameters,
- evaluate model performance using nested cross-validation,
- analyze model predictions using confusion matrices and classification reports.

The project aims to support automated agricultural sorting systems by reducing manual work and classification errors.

---

## Dataset

The project uses the Dry Bean Dataset from the UCI Machine Learning Repository.

Source:  
https://archive.ics.uci.edu/dataset/602/dry+bean+dataset

The dataset contains:

- 13,611 dry bean samples
- 16 numerical features
- 7 bean classes

Bean classes:

- SEKER
- DERMASON
- SIRA
- CALI
- HOROZ
- BARBUNYA
- BOMBAY

The features describe physical and geometric properties such as:

- area
- perimeter
- compactness
- roundness
- eccentricity
- shape factors

---

## Main Methods

The project includes:

- exploratory data analysis (EDA)
- outlier detection using IQR
- feature engineering
- nested cross-validation
- hyperparameter tuning with GridSearchCV
- Decision Tree classification
- Random Forest classification
- confusion matrix analysis
- precision, recall, and F1-score evaluation

---

## Main Results

Random Forest achieved the best overall performance.

Main results:

- Train Accuracy: 96.2%
- Test Accuracy: 91.1%

The model performed well across most bean classes, although some confusion remained between visually similar classes.

---

## Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Structure

- `dry_bean_supervised_classification.ipynb`  
  Main notebook containing preprocessing, model training, evaluation, and visualizations.

- `Dry_Bean_Dataset.xlsx`  
  Excel version of the dataset used in the project.

- `Dry_Bean_Dataset.arff`  
  Original ARFF version of the dataset.

---

## Author

Nur Bozdemir