# -AIML-Internship-Week5--SamiUrRehmanKhan
Built and compared multiple machine learning classification models on the Titanic dataset using Logistic Regression, KNN, Decision Tree, and Random Forest. Applied preprocessing, feature engineering, hyperparameter tuning, cross-validation, ROC analysis, confusion matrices, and dashboard visualization to evaluate survival prediction performance.

Overview

This project focuses on solving a binary classification problem using the Titanic Survival dataset. Multiple machine learning classification algorithms were implemented, evaluated, and compared using advanced classification metrics and visualization techniques.

The project covers the full machine learning workflow including:

Data preprocessing
Feature engineering
Model training
Hyperparameter tuning
Cross-validation
ROC & Precision-Recall analysis
Confusion matrix diagnostics
Learning curve analysis
Model persistence using Joblib
Professional dashboard visualization
Dataset
Titanic Survival Dataset

Target Variable:

Survived
1 = Survived
0 = Did Not Survive

Important Features:

Passenger Class (Pclass)
Gender (Sex)
Age
Fare
Family information (SibSp, Parch)
Embarked Port

Engineered Features:

FamilySize
IsAlone
log1p(Fare)
Libraries Used
Library	Purpose
Scikit-learn	Machine Learning models & evaluation
NumPy	Numerical computation
Pandas	Data manipulation
Matplotlib	Data visualization
Seaborn	Statistical plots
SciPy	Statistical analysis
Joblib	Model saving/loading
Models Implemented
1. Logistic Regression

Baseline linear classifier used for comparison.

2. K-Nearest Neighbours (KNN)

Distance-based classifier optimized using different K values and distance metrics.

3. Decision Tree

Tree-based classification with depth analysis and interpretability.

4. Random Forest

Ensemble learning model with hyperparameter tuning using GridSearchCV.

Key Techniques Applied
Data Preprocessing
Missing value handling
One-hot encoding
Feature scaling
Log transformation
Feature Engineering
FamilySize
IsAlone
Fare transformation
Hyperparameter Tuning
GridSearchCV
Cross-validation
Evaluation Metrics
Accuracy
Precision
Recall
F1-Score
ROC-AUC
Average Precision
Advanced Analysis
ROC Curves
Precision-Recall Curves
Confusion Matrix Analysis
Learning Curves
Cross-Validation Stability
Feature Importance Analysis
Important Visualizations

The project generates multiple professional visualizations including:

KNN K-value analysis
Decision Tree visualization
Random Forest feature importance
ROC curves
Precision-Recall curves
Cross-validation boxplots
Learning curves
Complete 6-chart dashboard
Over-confident prediction error analysis
Files Generated
Figures
week5_dashboard.png
roc_pr_curves.png
learning_curves.png
confusion_matrix_deep_dive.png
decision_tree_analysis.png
random_forest_feature_importance.png
Model Files
week5_best_model.pkl
Prediction Analysis
top_wrong_predictions.csv
Best Performing Model
Random Forest Classifier

Reasons:

Strong nonlinear learning capability
Reduced overfitting through ensemble learning
High ROC-AUC and F1 performance
Strong generalization across folds
Key Learnings

This project strengthened understanding of:

Classification workflows
Threshold-based evaluation
Precision vs Recall tradeoffs
Ensemble learning
Cross-validation strategies
ROC & PR analysis
Model interpretability
Pipeline-based ML development

**How to Run:**
Install Dependencies
pip install pandas numpy matplotlib seaborn scipy scikit-learn joblib
Run Notebook

Open the notebook in:

Google Colab
Jupyter Notebook

Run all cells sequentially.

Project Outcome

This project demonstrates a complete professional classification workflow using real-world machine learning practices. It highlights the importance of evaluation metrics, model comparison, and diagnostic analysis in building reliable predictive systems.
