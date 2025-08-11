# Task5 : Decision Trees and Random Forests

**Overview**

This repository contains the solution for Task 5 of the Elevate AI & ML Internship. The goal of this task was to learn and implement tree-based models for both classification and regression, analyze overfitting, interpret feature importance, and compare performance between Decision Trees and Random Forests.

**Dataset**

For this task, the Heart Disease Dataset was used. It contains patient health metrics to predict the presence of heart disease.


 **Tools and Libraries Used**

Python 3.x

Scikit-learn

Graphviz

**Task Steps**
1. Train a Decision Tree Classifier

Trained using DecisionTreeClassifier from scikit-learn.

Visualized the tree using Graphviz.

2. Control Tree Depth and Prevent Overfitting

Adjusted parameters like max_depth and min_samples_split.

Compared training vs testing accuracy.

3. Train a Random Forest Model

Used RandomForestClassifier to combine multiple decision trees.

Compared accuracy with the single Decision Tree model.

4. Interpret Feature Importances

Extracted and visualized feature importance scores from the models.

6. Evaluate Using Cross-Validation
   
Applied k-fold cross-validation to assess model stability.

**How to Run**

Install required libraries: scikit-learn, graphviz, pandas, matplotlib.

Download the dataset from the provided link.

Run the script or notebook to train models and view results.

**What I Learned**

How decision trees split data based on feature conditions.

The importance of controlling tree complexity to avoid overfitting.

How Random Forest improves generalization.

How to interpret model features and evaluate accuracy with cross-validation.

**Submission**
This repository is submitted as part of the Elevate AI & ML Internship - Task 5.
