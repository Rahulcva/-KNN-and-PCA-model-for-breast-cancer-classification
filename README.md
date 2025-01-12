# -KNN-and-PCA-model-for-breast-cancer-classification

# Dataset

The dataset used for this project is the **Breast Cancer Wisconsin (Diagnostic) Dataset**, available from the UCI Machine Learning Repository. It contains various features related to cell nuclei present in breast cancer biopsies.

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
- **Number of Instances**: 569
- **Number of Features**: 30 numeric features + 1 target feature (diagnosis)

## Methodology

### 1. **Data Preprocessing**:
   - Loaded and cleaned the dataset.
   - Encoded the target variable (`diagnosis`) from categorical ('M' for malignant and 'B' for benign) to numeric values (1 for malignant, 0 for benign).
   - Scaled the feature data using **StandardScaler** to standardize the features.

### 2. **Principal Component Analysis (PCA)**:
   - Performed PCA to reduce the dimensionality of the feature space and retain most of the variance in the data.

### 3. **Model**:
   - Used the **K-Nearest Neighbors (KNN)** classifier to train the model on the processed dataset.
   - Achieved an **accuracy of 98%** on the test set after applying PCA.

## Results

The model achieved an accuracy of 98% on the test data, demonstrating high performance in classifying breast cancer tumors as either malignant or benign.
