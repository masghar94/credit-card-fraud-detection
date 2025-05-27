# credit-card-fraud-detection
Hybrid deep learning system using ANN and Autoencoder to detect fraud.
# Credit Card Fraud Detection with ANN and Autoencoder

This project applies deep learning techniques to detect fraudulent credit card transactions.

## 🔍 Dataset
- Kaggle Credit Card Fraud Dataset
- 284,807 transactions with only 492 fraud cases (0.17%)

## 📌 Approach
- **Artificial Neural Network (ANN)**: Binary classification using ReLU layers and dropout
- **Autoencoder**: Trained on normal data to detect anomalies via reconstruction error
- **Hybrid Model**: Used reconstruction error as a feature in a calibrated Random Forest

## 📈 Performance
- ANN ROC AUC: 0.98
- Hybrid Model ROC AUC: 0.9997
- Strong balance between precision and recall

## 📂 Notebooks
- `Asghar_ANN.ipynb`: Builds and evaluates ANN model
- `autoencoderMAP_(1).ipynb`: Autoencoder anomaly detection & hybrid model creation

