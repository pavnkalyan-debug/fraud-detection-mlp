# fraud-detection-mlp
fraud detection using MLP perceptron
# Credit Card Fraud Detection using MLP Perceptron

This repository contains a deep learning project focused on detecting fraudulent credit card transactions. The system utilizes a Multilayer Perceptron (MLP) architecture to identify patterns in transaction data and classify them as legitimate or fraudulent.

## Project Overview
The project implements a supervised learning approach using PyTorch. Given the high class imbalance common in fraud datasets, the workflow emphasizes proper data scaling and robust evaluation metrics beyond simple accuracy.

## Key Features
* **Neural Network Architecture:** A custom MLP model with Dropout layers to prevent overfitting and ReLU activation for non-linearity.
* **Automated Data Pipeline:** Uses the `kagglehub` library to dynamically fetch the Credit Card Fraud Detection dataset.
* **Feature Engineering:** Includes automated scaling of transaction time and amount using `StandardScaler`.
* **Comprehensive Metrics:** Evaluation includes Precision-Recall analysis and F1-scoring to ensure reliable fraud detection.

## How to Run
1. **Clone the Repo:** 
   `git clone https://github.com/pavnkalyan-debug/fraud-detection-mlp.git`
2. **Install Requirements:** 
   `pip install -r requirements.txt`
3. **Execute:** 
   Open `fraud_detection.ipynb` in Jupyter or Google Colab and run all cells.

## Technologies Used
* **Python**
* **PyTorch** (Deep Learning Framework)
* **Pandas & NumPy** (Data Processing)
* **Scikit-Learn** (Preprocessing & Evaluation)
* **Matplotlib & Seaborn** (Data Visualization)
