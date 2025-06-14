# 🧠 Spam Classification with Regularized Neural Networks

This project builds a binary text classifier to distinguish **spam** from **ham (non-spam)** messages using a fully connected neural network. The goal is to evaluate how different **regularization techniques** affect the model’s generalization performance.

## 🔍 Overview

- **Dataset**: SMS Spam Collection Dataset (`spam.csv`)
- **Text Vectorization**: TF-IDF with English stopwords removal
- **Model**: Feedforward neural network with configurable regularization
- **Regularization Methods Compared**:
  - No regularization
  - L1 (Lasso)
  - L2 (Ridge)
  - Dropout
  - Batch Normalization
- **Evaluation**:
  - Accuracy and loss plotted per epoch
  - Final validation accuracy compared via bar chart

## 📈 Final Comparison

The final validation accuracy for each regularization type is displayed in a bar chart, with clear visual differentiation and numeric labels.

<p align="center">
  <img src="images/validation_accuracy_comparison.png" width="600" alt="Accuracy Plot">
</p>
