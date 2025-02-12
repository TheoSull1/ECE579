# ECE579
Income Classification Using 1996 US Census Data

Project Overview

This project classifies individuals' income levels based on 1996 US Census data, predicting whether an individual's income is above or below $50,000 annually using a Decision Tree Classifier (C4.5 algorithm).

Dataset

Source: 1996 US Census Income Dataset
Features:
Demographic: Age, race, sex, marital status, native country
Education & Work: Workclass, education level, occupation, relationship, fnlwgt
Financial: Capital gain, capital loss, hours per week
Target Variable: Income ( >$50k or <=$50k )
Technologies Used

Python with the following libraries:
scikit-learn (DecisionTreeClassifier, LabelEncoder)
matplotlib, seaborn (visualizations)
pandas, numpy (data processing)
Methodology

Preprocessing:
Handled missing values with mode imputation
Encoded categorical attributes using LabelEncoder
70/30 train-test split
Model:
Used C4.5 Decision Tree Classifier
Tuned max_depth and max_features to balance accuracy and overfitting
Results:
Final Accuracy: 84%
Key Features: Capital gain, relationship status, education level
Project Files

📂 income_classification.ipynb – Code implementation
📄 requirements.txt – Dependencies
How to Run


Install dependencies:
pip install -r requirements.txt
