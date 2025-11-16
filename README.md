# Diabetes Risk PCA-KNN Project

## Description  
This project analyzes the Diabetes Risk dataset using **Principal Component Analysis (PCA)** and compares the performance of a **KNeighborsClassifier** before and after dimensionality reduction. The goal is to evaluate how PCA affects training time, efficiency, and overall model performance.

## Dataset  
- Source: [Google Drive link](https://drive.google.com/file/d/1CE2giLLTp0Cjn0bn9hmtCWIxGZf8_uO1/view)  
- Contains multiple features related to diabetes risk factors.  
- Includes preprocessing steps such as handling missing values, scaling, and train-test splitting.

## Methodology  
1. Data preprocessing (imputation, scaling)  
2. Applying PCA to extract principal components  
3. Training KNN on:  
   - Original data  
   - Data after PCA  
4. Evaluating performance using:  
   - **Training time**  
   - Classification accuracy  
   - Model efficiency

## Results  
- Without PCA: Training time ≈ **0.611879 seconds**  
- With PCA: Training time ≈ **0.282555 seconds**  
- PCA significantly reduces training time while maintaining similar model performance.

## Installation & Usage  

```bash
# Clone the repository
git clone https://github.com/your-username/diabetes-risk-pca-knn.git
cd diabetes-risk-pca-knn

# Optional: create a virtual environment
python -m venv venv
source venv/bin/activate  # Linux / Mac
.\venv\Scripts\activate   # Windows

# Install dependencies
pip install -r requirements.txt
