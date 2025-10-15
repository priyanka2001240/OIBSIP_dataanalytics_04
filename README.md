# OIBSIP_dataanalytics_04
Task 4: Multi-Class Prediction of Wine Quality
Internship

Oasis Infobyte – Data Science Internship (Virtual)

Project Goal

The aim of this project was to develop a Multi-Class Classification Model capable of predicting Wine Quality ratings based on its chemical composition.
By leveraging various Machine Learning algorithms, this project sought to identify the most influential chemical properties affecting wine quality and build a high-performing predictive system for quality assessment.

Dataset

The project utilized the Wine Quality Dataset, containing physicochemical variables such as Fixed Acidity, Volatile Acidity, Citric Acid, Residual Sugar, Density, Alcohol, and pH.
The target variable, Quality, represents the wine’s taste rating on a numerical scale.

Key Steps & Methodology

Exploratory Data Analysis (EDA):

Analyzed feature distributions to understand chemical variability.

Visualized the Correlation Matrix to identify highly correlated predictors.

Discovered strong correlations between Alcohol and Quality, and a negative relation with Volatile Acidity.

Data Preprocessing:

Split the data into Training (80%) and Testing (20%) sets.

Standardized numerical features to ensure balanced model training.

Prepared clean, scaled data for model benchmarking.

Model Building & Benchmarking:

Trained and compared three models:

Random Forest Classifier 

Support Vector Classifier (SVC)

SGD Classifier (Stochastic Gradient Descent)

Integrated Standard Scaling within SVC and SGD pipelines for fair evaluation.

Model Validation & Evaluation:

Applied 5-Fold Cross-Validation to ensure model generalization.

Evaluated results using Classification Reports and Confusion Matrices.

Identified Random Forest as the top-performing model with balanced precision and recall across classes.

Feature Importance & Insights:

Alcohol and Volatile Acidity emerged as the strongest predictors of wine quality.

Visualized feature importance to highlight key chemical factors influencing taste ratings.

Tools and Libraries

Python

Pandas & NumPy: Data handling and analysis.

Matplotlib & Seaborn: EDA and visualization (feature plots, correlation heatmap).

Scikit-learn (sklearn): train_test_split, StandardScaler, RandomForestClassifier, SVC, SGDClassifier, cross_val_score, classification_report.

Actionable Conclusions & Model Outcome

The Random Forest Model achieved the most consistent and interpretable performance.

Key chemical properties like Alcohol and Volatile Acidity play a critical role in determining wine quality.

Demonstrates the importance of combining EDA insights with robust model evaluation for reliable predictions.

File Structure

wine_quality_classification.py – Main script containing full ML pipeline and model comparison.

winequality.csv – Dataset containing physicochemical attributes and quality scores.

README.md – Documentation file (this file).
