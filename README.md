📊 Breast Cancer Classification with PCA
🚀 Project Overview

This project applies Principal Component Analysis (PCA) for dimensionality reduction on the Breast Cancer dataset and evaluates its impact on classification performance using Logistic Regression.

The goal is to compare model performance:

✅ Without PCA

✅ With PCA (2 principal components)

📁 Dataset

The dataset used is:

👉 sklearn.datasets.load_breast_cancer

It contains:

569 samples

30 numerical features

Binary classification:

Malignant

Benign

🛠 Technologies Used

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-Learn

🔍 Project Workflow  

1️⃣ Data Loading & Exploration

Load dataset from sklearn

Convert to pandas DataFrame

Explore shape and description

2️⃣ Feature Scaling

Standardize features using StandardScaler

Important before applying PCA

3️⃣ PCA Dimensionality Reduction

Reduce features from 30 → 2 components

Visualize transformed data

Plot feature contribution using heatmap

4️⃣ Model Training

Train Logistic Regression in two cases:

🔵 Model 1 — Without PCA

Train on original 30 features

Compute accuracy

🔴 Model 2 — With PCA

Train on 2 principal components

Compute accuracy

5️⃣ Model Comparison

Compare accuracy before and after PCA.

📊 Results

The output shows:

Accuracy Before PCA

Accuracy After PCA

Comparison Table

Example:

Model            	Accuracy

Without PCA	       0.xx

With PCA         	0.xx

📈 Visualization

The project includes:

Scatter plot of PCA components

Heatmap of PCA feature importance
