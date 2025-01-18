# Microsoft Malware Prediction

This project demonstrates a comprehensive approach to detecting malware using a combination of Machine Learning (ML) and Deep Learning (DL) models, alongside MLflow for experiment tracking.

## Enhanced Overview
1. **Data Preprocessing**: Handled missing values, treated skewness, and controlled outliers to ensure data quality.  
2. **Feature Selection**: Applied Chi-Square, ANOVA, Mutual Information, and Kendall’s Tau to identify top predictors.  
3. **Dimensionality Reduction**: Performed LDA, t-SNE, and UMAP to visualize and reduce feature space.  

## Machine Learning Algorithms
- **Logistic Regression**  
    Uses the logit function to model malware probability.  
    Accuracy: 50.47%

- **K-Nearest Neighbors (KNN)**  
    Classifies by majority vote of nearest neighbors.  
    Accuracy: 51.52%

- **Random Forest**  
    Combines multiple decision trees to reduce overfitting via bagging.  
    Accuracy: 60.84%

- **Decision Tree**  
    Splits features recursively for interpretability.  
    Accuracy: 56.09%

- **AdaBoost**  
    Iteratively adjusts weights to emphasize misclassified samples.  
    Accuracy: 62.65%

- **Gradient Boosting (GBM)**  
    Minimizes residuals incrementally by adding weak learners.  
    Accuracy: 62.84%

- **XGBoost**  
    Highly efficient tree boosting with advanced regularization.  
    Accuracy: 63.87%

- **LightGBM**  
    Uses leaf-wise growth and gradient-based sampling.  
    Accuracy: 63.72%

- **CatBoost**  
    Handles categorical features internally, reducing manual encoding.  
    Accuracy: 63.98%

### Top 3 ML Algorithms
1. CatBoost 
2. XGBoost  
3. LightGBM  

## Deep Learning Algorithms
- **Multi-Layer Perceptron (MLP)**  
    A dense network that learns nonlinear boundaries with backpropagation.
    Accuracy: 62.68%
- **Gated Recurrent Unit (GRU)**  
    Manages time-dependent data via gating mechanisms in recurrent layers.
    Accuracy: 62.93%
- **Autoencoder**  
    Learns efficient encodings and reconstructs inputs for feature extraction.
    Accuracy: 62.45%

## MLflow Usage
MLflow tracks experiments centrally, storing metrics (accuracy, precision, recall, AUC) and model artifacts. It integrates seamlessly with various libraries, enabling comparison of runs on a local or remote MLflow UI.

## Usage
1. Clone the repository and install dependencies.  
2. Run scripts or notebooks for data preprocessing, feature selection, dimensionality reduction, and model training.  
3. Launch the MLflow UI to monitor performance, compare runs, and track model versions.
