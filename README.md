<div align="center">

# Food Category Classification Using K-Nearest Neighbors (KNN)

### Machine Learning Classification Project Using Nutritional Food Data, Feature Scaling, and Distance-Based Prediction Analysis

</div>

---

# Project Overview

This project demonstrates the implementation of the **K-Nearest Neighbors (KNN) Classification Algorithm** on a food nutrition dataset to classify food-related categories using nutritional information and meal characteristics.

The notebook focuses on understanding how KNN uses similarity and distance between data points to make predictions.

Instead of learning through theory only, this project explores KNN practically through:
- preprocessing
- encoding
- normalization
- visualization
- prediction analysis
- and classification workflow implementation

The complete project was developed step by step using Python and Scikit-learn.

---

# Problem Statement

Can machine learning classify food-related categories using nutritional values and meal information?

This project attempts to analyze food records using features such as:
- Calories
- Protein
- Carbohydrates
- Fat
- Fiber
- Sugars
- Sodium
- Cholesterol
- Water Intake
- Meal Type

and apply the KNN algorithm to classify food-related patterns based on nearest neighboring data points.

---

# Dataset Workflow

The dataset contains nutritional and meal-related records describing different food items and dietary attributes.

The workflow was designed to simulate a complete beginner machine learning classification pipeline including:
- preprocessing
- feature transformation
- normalization
- visualization
- model training
- prediction
- and evaluation

---

# Project Workflow

---

## Step 1: Import Libraries

Python libraries were imported for:
- data handling
- preprocessing
- visualization
- machine learning implementation

Libraries used:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Step 2: Load Dataset

The food nutrition dataset was loaded and explored using Pandas to inspect:
- dataset structure
- feature types
- numerical columns
- categorical columns

---

## Step 3: Data Preprocessing & Heatmap Analysis

The dataset was checked carefully for missing values and overall data quality.

A heatmap was created to visually inspect null values across all columns.

The dataset contained:
- no missing values
- structured nutritional records
- clean feature distribution

This made the preprocessing workflow smoother and easier to implement.

---

## Step 4: Encoding of Categorical Features

Categorical columns such as:
- Food_Item
- Category
- Meal_Type

were converted into numerical format using encoding techniques.

This step allowed the KNN model to process categorical food-related information mathematically.

---

## Step 5: Feature Normalization

Since KNN is highly dependent on distance calculations, feature scaling was an important step in this project.

Normalization was applied using:

MinMaxScaler()

to bring all nutritional features into a balanced numerical range.

This helped improve distance calculations between neighboring data points.

---

## Step 6: Pairplot & Feature Relationship Analysis

Pairplots were created for selected features to visually inspect:

feature relationships
distributions
patterns
and partial linearity between nutritional attributes

This step helped understand how food-related features interact with each other before model training.

---

## Step 7: Train-Test Split

The dataset was divided into:

Training dataset
Testing dataset

to evaluate model performance on unseen food records.

---

## Step 8: Apply KNN Model

The K-Nearest Neighbors Classification Algorithm was implemented using Scikit-learn.

The model classified food-related records by analyzing nearby neighboring data points using distance-based calculations.

---

## Step 9: Prediction & Accuracy Analysis

Predictions were generated using testing data to evaluate model performance.

The model achieved approximately:

<div align="center">
67% Accuracy
</div>

This accuracy helped demonstrate how KNN behaves on nutritional datasets and how feature selection and data distribution influence classification performance.

---

## Step 10: Visualization

Visualizations were created to analyze:

feature distributions
prediction behavior
and model understanding

Although the visualization results were not perfectly separated, they still helped explore how KNN classification behaves with nutritional data and normalized features.

---

# Technologies Used

<div align="center">

| Technology | Role in Project |
|---|---|
| **Python** | Built the complete machine learning workflow and model implementation |
| **Pandas** | Loaded, explored, and handled the food nutrition dataset |
| **NumPy** | Supported numerical computations and array operations |
| **Matplotlib** | Created plots, graphs, and visualization outputs |
| **Seaborn** | Generated heatmaps, pairplots, and statistical visualizations |
| **Scikit-learn** | Applied preprocessing, normalization, train-test splitting, and KNN classification |

</div>

---

# What This Project Demonstrates

This repository demonstrates:

practical implementation of KNN Classification
preprocessing workflow
feature encoding
feature normalization
nutritional data analysis
pairplot visualization
classification workflow
prediction analysis
and machine learning experimentation using food-related data

---

# Learning Outcome

This project was developed to strengthen understanding of:

KNN Classification
distance-based machine learning
normalization importance
preprocessing workflows
feature scaling
categorical encoding
visualization techniques
and classification model implementation

The notebook combines preprocessing, scaling, classification, evaluation, and visualization into a complete beginner-friendly machine learning workflow.

---

<div align="center">
Repository Includes

Heatmap Analysis • Encoding • MinMaxScaler • Pairplots • KNN Classification • Prediction Analysis • Visualization • Food Nutrition Data Analysis

</div>
