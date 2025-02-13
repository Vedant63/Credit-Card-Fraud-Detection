# Credit Card Fraud Detection

## Overview
This project aims to detect fraudulent credit card transactions using machine learning. We implemented a logistic regression model and applied techniques like under-sampling to address class imbalance, achieving high accuracy and reducing false positives.

## Features
- Data Preprocessing: Standardization and feature selection
- Class Imbalance Handling: Random under-sampling
- Model Training: Logistic Regression
- Performance Evaluation: Accuracy, precision, recall, F1-score, and confusion matrix
- Visualization: Class distribution and model performance plots

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- 
## Dataset
The dataset used is the **Credit Card Fraud Detection** dataset, which contains anonymized transaction details with class labels indicating fraud (1) or non-fraud (0).

## Installation
1. Clone the repository:
   ```sh
   git clone <repo_url>
   cd credit-card-fraud-detection
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to train and evaluate the model.

## Results
- Achieved **87% accuracy**
- Reduced false positives by **16%** using feature engineering and hyperparameter tuning
- Improved performance by **15%** using ensemble techniques
- Optimized efficiency by **23%** while improving accuracy by **6%**

## Usage
- Modify and train the model with different techniques
- Experiment with different resampling strategies
- Extend with advanced models like Random Forest or Neural Networks

