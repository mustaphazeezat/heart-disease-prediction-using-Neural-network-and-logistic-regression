# Heart Disease Classification

This project compares two machine learning models for binary classification using a heart disease dataset.

## Models

**1. Neural Network (Keras)**

- Normalized numerical features and one-hot encoded categorical features.
- Trained a neural network with 6 hidden neurons.
- This configurations achieved 84.75% test accuracy.

**2. Logistic Regression (scikit-learn)**

- Scaled numerical features and one-hot encoded categorical features.
- Achieved 86.44% test accuracy and 0.296 test log loss.

## Results

| Model | Test Accuracy |
|---|---:|
| Neural Network (6 neurons) | 84.75% |
| Logistic Regression | 86.44% |

Logistic regression performed slightly better than the neural network on the test set. The neural network showed a gap between training and validation accuracy, suggesting possible overfitting.

## Key Learning

This project provided practical experience in data preprocessing, binary classification, model evaluation, and comparing a neural network with a traditional machine learning model.
