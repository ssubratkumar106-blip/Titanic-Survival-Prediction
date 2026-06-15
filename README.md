# Titanic Survival Prediction Using Machine Learning

## Project Overview

This project demonstrates the implementation of a supervised machine learning model to predict passenger survival on the Titanic using historical passenger data.

The project covers data preprocessing, feature engineering, model training, prediction, and performance evaluation using a Decision Tree Classifier.

---

## Objective

To build a predictive machine learning model capable of determining whether a passenger survived the Titanic disaster based on various passenger attributes.

---

## Dataset

Dataset: Titanic Passenger Dataset

Features Used:

* Pclass
* Sex
* Age
* SibSp
* Parch
* Fare
* Embarked

Target Variable:

* Survived

  * 0 = Did Not Survive
  * 1 = Survived

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Machine Learning Workflow

### Data Preprocessing

* Removed unnecessary columns
* Handled missing values
* Encoded categorical variables
* Prepared feature and target datasets

### Train-Test Split

* Training Data: 80%
* Testing Data: 20%

### Model Used

Decision Tree Classifier

### Model Training

The model was trained using the training dataset and evaluated on unseen test data.

---

## Model Performance

### Accuracy Score

77.09%

### Confusion Matrix

| Actual / Predicted | 0  | 1  |
| ------------------ | -- | -- |
| 0                  | 80 | 25 |
| 1                  | 16 | 58 |

Interpretation:

* Correctly predicted non-survivors: 80
* Correctly predicted survivors: 58
* False positives: 25
* False negatives: 16

---

## Visualization

The project includes:

* Confusion Matrix Heatmap
* Model Accuracy Evaluation
* Data Exploration Visualizations

---

## Project Structure

Titanic-Survival-Prediction/

├── titanic.csv

├── predictive_model.ipynb

├── confusion_matrix.png

├── README.md

---

## Key Learnings

Through this project, I gained hands-on experience in:

* Data Cleaning
* Feature Engineering
* Supervised Learning
* Decision Tree Classification
* Model Evaluation
* Confusion Matrix Analysis
* Machine Learning Workflow

---

## Future Improvements

* Random Forest Classifier
* Logistic Regression
* Hyperparameter Tuning
* ROC Curve Analysis
* Cross Validation

---

## Author

Subrat Kumar Sahoo

B.Tech Computer Science & Engineering

Machine Learning Internship Project

2026
