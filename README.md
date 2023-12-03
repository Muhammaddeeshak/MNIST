
## MNIST Dataset Exploration and Binary Classification

This repository focuses on the exploration and transformation of the MNIST dataset using Python's `sklearn` library, transforming it into a binary classification task. The following steps are undertaken:

1. **Data Loading and Exploration**:
   - Load the MNIST dataset from `sklearn`.
   - Conduct exploratory analysis to understand the data's structure.

2. **Data Standardization**:
   - Standardize the data for uniformity.

3. **Binary Classification Transformation**:
   - Convert the multi-class problem into a binary classification task.

4. **Data Splitting**:
   - Split the dataset into training (60,000 samples) and testing (10,000 samples) sets.

5. **Dimensionality Reduction**:
   - Apply PCA or LDA techniques to reduce dimensions while retaining 95% of the explained variance ratio.
   - Plot useful eigenvalues and cumulative explained variance ratio to showcase dimensionality reduction effectiveness.

6. **Model Training**:
   - Utilize an appropriate classifier to train on the transformed dataset.

7. **Performance Evaluation**:
   - Plot decision/recall curves to visualize classifier performance.
   - Plot ROC curves for further performance analysis.

