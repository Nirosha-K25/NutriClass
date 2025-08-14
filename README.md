# NutriClass
**NutriClass: Food Classification Using Nutritional Data**

**Problem Statement:**
In the era of increasing dietary awareness, the ability to classify food items based on nutritional attributes are invaluable. This project involves developing a machine learning model that classifies food into multiple categories using tabular data such as calories, proteins, carbohydrates, fats, and sugar. By the end of this project,  we will be able to create a robust classification system that can accurately label food types and gain insights into what makes each food category distinct. management systems.

**Business Use Cases:**
Smart Dietary Applications: Recommend food based on nutritional balance.
Health Monitoring Tools: Assist nutritionists in classifying food for diet planning.
Food Logging Systems: Automatically classify user entries for food-tracking apps.
Educational Platforms: Help learners understand food categories and nutrition through AI.
Grocery/Meal Planning Apps: Auto-suggest replacements within same category

**Approach:**
**Data Understanding and Exploration**
Load the food tabular dataset and examine class distribution.
Visualize sample entries (rows) to understand inter-class variation.
Check dataset size, imbalance, and noise levels.
**Data Preprocessing**
Handle missing values (e.g., impute or drop rows with NaNs).
Detecting and removing or cap outliers.
Normalize or standardize numerical features.
**Feature Engineering**
Use PCA or feature selection to reduce dimensionality.
Encode class labels using label encoding or one-hot encoding.

**Model Selection and Training**
Train and compare multiple classifiers:
Logistic Regression
Decision Tree
Random Forest
K-Nearest Neighbors
Support Vector Machine
XGBoost
Gradient Boosting Classifier

**Results: **
Expected outcomes include:
A benchmark comparison of traditional ML models on food classification.
Insight into which feature extraction and model combination performs best.

Visual performance metrics showcasing model behavior.
