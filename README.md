# German Credit Dataset Analysis

## Overview

This project analyzes the German Credit Dataset to cluster customers and classify loan applicants as either Good or Bad credit risks. The dataset comprises 1000 entries with various attributes, and the goal is to perform exploratory data analysis (EDA), clustering, and classification.

## Tasks Performed

1. **Exploratory Data Analysis (EDA) and Data Cleaning:**
   - Investigated the dataset for missing values and anomalies.
   - Removed irrelevant columns with obscure descriptions.

2. **One-Hot Encoding:**
   - Applied one-hot encoding for categorical variables.

3. **Histogram Visualization:**
   - Visualized histograms of numerical features.
   - Applied log transformation to normalize data.

4. **Feature Scaling:**
   - Ensured consistent scaling of numerical features.

5. **Clustering:**
   - Selected numerical features for clustering.
   - Utilized the elbow method to find optimal clusters.

6. **Dimensionality Reduction (PCA):**
   - Used PCA to visualize clusters in lower-dimensional space.

7. **Modeling and Evaluation:**
   - Implemented K-Fold Cross-Validation with a chosen classifier.
   - Reported evaluation metrics.

## Files Included

- `GermanCreditAnalysis.ipynb`: Jupyter notebook with analysis code.
- `readme.md`: This file, providing an overview and instructions.

## How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/german-credit-analysis.git
   cd german-credit-analysis
