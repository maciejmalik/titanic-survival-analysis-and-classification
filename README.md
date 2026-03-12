# Titanic Survival Analysis and Classification

This repository contains a data analysis and machine learning project based on the Titanic dataset.  
The project is divided into two notebooks: one focused on exploratory data analysis and preprocessing, and the second focused on training and evaluating classification models.

## Project goal
The goal of this project is to prepare Titanic passenger data and build models that predict whether a passenger survived (`1`) or not (`0`).

## Repository contents

- `Titanic_EDA.ipynb`  
  Notebook containing data exploration, cleaning, preprocessing, missing value handling, feature transformation, and visual analysis.

- `Titanic_Model.ipynb`  
  Notebook containing machine learning workflow, train-test split, model training, and evaluation of classification models.

## Workflow
The project is organized into two main steps:

1. **EDA and preprocessing**
   - loading the Titanic dataset
   - removing less useful columns
   - handling missing values
   - transforming categorical variables
   - preparing the dataset for modeling

2. **Modeling and evaluation**
   - selecting features and target
   - splitting data into training and test sets
   - training classification models
   - evaluating results using accuracy, confusion matrix, and F1-score

## Models used
- Dummy Classifier
- Decision Tree Classifier
- Support Vector Machine (SVM)

## Tools and libraries
- Python
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn

## Notes
The notebooks include comments and explanations directly in the code.  
The first notebook focuses on data preparation, while the second presents the machine learning part of the project.

## Dataset
The project uses the Titanic dataset for binary classification of passenger survival.
