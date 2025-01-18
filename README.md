# Microsoft Malware Prediction

This project demonstrates a comprehensive approach to detecting malware using a combination of Machine Learning (ML) and Deep Learning (DL) models, alongside MLflow for experiment tracking.


## Table of Contents

- [Enhanced Overview](#enhanced-overview)
- [Clone the Repository](#clone-the-repository)
- [Machine Learning Algorithms](#machine-learning-algorithms)
- [Top 3 ML Algorithms](#top-3-ml-algorithms)
- [Deep Learning Algorithms](#deep-learning-algorithms)
- [MLflow Integration](#mlflow-integration)


## Enhanced Overview
1. **Data Preprocessing**: Handled missing values, treated skewness, and controlled outliers to ensure data quality.  
2. **Feature Selection**: Applied Chi-Square, ANOVA, Mutual Information, and Kendall’s Tau to identify top predictors.  
3. **Dimensionality Reduction**: Performed LDA, t-SNE, and UMAP to visualize and reduce feature space.  

## Clone the Repository

To start using this project, first, clone the repository:

```bash
git clone https://github.com/Abdelrahman-Elshahed/Microsoft_Maleware_Prediction_Kaggle_Competition.git
```


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
![Image](https://github.com/user-attachments/assets/60dda137-6534-4685-bfa3-2266a17315bf)

2. XGBoost  
![Image](https://github.com/user-attachments/assets/05268524-d7fa-4629-bd98-e1182dfdb569)

3. LightGBM  
![Image](https://github.com/user-attachments/assets/ba3dd60a-e056-4484-8dd3-3cedcf8fa5d4)

## Deep Learning Algorithms
- **Multi-Layer Perceptron (MLP)**  
    A dense network that learns nonlinear boundaries with backpropagation.
    Accuracy: 62.68%
  ![Image](https://github.com/user-attachments/assets/79fb111d-27ac-4ea7-9090-faa7ce9d427a)

- **Gated Recurrent Unit (GRU)**  
    Manages time-dependent data via gating mechanisms in recurrent layers.
    Accuracy: 62.93%
  ![Image](https://github.com/user-attachments/assets/436d094a-0c48-47d1-bf7d-479872bd5574)

- **Autoencoder**  
    Learns efficient encodings and reconstructs inputs for feature extraction.
    Accuracy: 62.45%
  ![Image](https://github.com/user-attachments/assets/7aee9441-d8c5-47cf-ad5e-5fe480ae5e26)

## MLflow Integration
MLflow tracks experiments centrally, storing metrics (accuracy, precision, recall, AUC) and model artifacts. It integrates seamlessly with various libraries, enabling comparison of runs on a local or remote MLflow UI.
![Image](https://github.com/user-attachments/assets/06b1a3f3-e84b-489d-a188-aa74d7bba144)
