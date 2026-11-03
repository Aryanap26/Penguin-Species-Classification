# Penguin Species Classification Using Machine Learning

## Project Overview

This project uses Machine Learning algorithms to classify penguins into three different species: Adelie, Chinstrap, and Gentoo.

Two classification algorithms, K-Nearest Neighbors (KNN) and Decision Tree, are implemented and compared based on their performance.

## Objectives

* Understand and preprocess the Palmer Penguins dataset.
* Perform data cleaning and visualization.
* Implement KNN and Decision Tree algorithms.
* Evaluate model performance using accuracy, classification reports, and confusion matrices.
* Compare both machine learning algorithms.

## Dataset

**Dataset:** Palmer Penguins Dataset

**Source:** https://github.com/allisonhorst/palmerpenguins

### Features Used

* Bill Length (mm)
* Bill Depth (mm)
* Flipper Length (mm)
* Body Mass (g)

### Target Variable

* Adelie
* Chinstrap
* Gentoo

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Methodology

1. Dataset Collection
2. Data Understanding
3. Data Cleaning
4. Data Visualization
5. Train-Test Splitting
6. Feature Scaling for KNN
7. Model Training
8. Model Evaluation
9. Cross Validation
10. Model Comparison

## Machine Learning Algorithms

### 1. K-Nearest Neighbors (KNN)

KNN classifies a penguin based on the nearest data points.

* Test Accuracy: 100%
* 5-Fold Cross Validation Accuracy: 98.83%

### 2. Decision Tree

Decision Tree classifies penguins using decision rules based on their features.

* Test Accuracy: 100%
* 5-Fold Cross Validation Accuracy: 96.78%

## Model Comparison

| Evaluation Metric         |    KNN | Decision Tree |
| ------------------------- | -----: | ------------: |
| Test Accuracy             |   100% |          100% |
| Cross Validation Accuracy | 98.83% |        96.78% |

Both models achieved 100% accuracy on the test dataset. KNN achieved higher average cross-validation accuracy.

## Project Files

* `Penguin_Species_Classification.ipynb` – Complete implementation.
* `Confusion_Matrix.png` – KNN confusion matrix.
* `Decision_Tree_Confusion_Matrix.png` – Decision Tree confusion matrix.
* `README.md` – Project documentation.

## Team Members

1. Aryan Prajapati – KU2000017013
2. Kalp Prajapati – KU2000016633
3. Rudra Patel – KU2000016663

## Institution

Karnavati University
Department of Computer Science Engineering
Specialization: Cyber Security

## Conclusion

Both KNN and Decision Tree successfully classified all 69 test samples. KNN achieved 98.83% average cross-validation accuracy, while Decision Tree achieved 96.78%. Based on cross-validation performance, KNN showed slightly better consistency on this dataset.
