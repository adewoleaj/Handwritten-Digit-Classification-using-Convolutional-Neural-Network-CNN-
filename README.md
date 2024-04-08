# Handwritten Digit Classification using Convolutional Neural Network (CNN)

## Introduction
This repository contains the implementation of a Convolutional Neural Network (CNN) for accurately classifying handwritten digits in the MNIST dataset. The primary objective is to leverage deep learning techniques to achieve high accuracy in digit recognition tasks. The MNIST dataset, a benchmark in the field of machine learning, is accessible through the following URL: [MNIST Dataset](http://yann.lecun.com/exdb/mnist).

## Installation
To run the code in this repository, you need to have the following libraries installed:
- TensorFlow
- Keras
- Matplotlib
- NumPy

You can install these libraries using pip:
```bash
pip install tensorflow keras matplotlib numpy
```

## Methodology
The project methodology involves preprocessing the MNIST dataset and developing a base CNN model. Various optimization techniques, including different optimizers and regularization methods such as dropout and L1/L2 regularization, are explored. Additionally, the impact of adjusting the CNN architecture's convolutional blocks and learning rates on model performance is investigated. Measures to identify and mitigate overfitting are also implemented.

## Results and Discussion
### Optimizer Selection
An analysis is conducted to determine the optimal optimizer for the CNN model. The Adam optimizer demonstrates superior performance compared to RMSprop and SGD, achieving a high accuracy rate of 98%.

### Effect of Regularization Methods
Different regularization techniques are applied to enhance the model's performance. Increasing the dropout rate and employing early stopping yield improvements, while L1 and L2 regularization show marginal effects on accuracy.

### Effect of Convolution Layers and Learning Rate
Increasing the number of convolutional layers and optimizing the learning rate contribute to enhancing the model's accuracy. A learning rate of 0.001 and a CNN architecture with three convolutional layers yield optimal results.

### Case of Overfitting
Some instances of overfitting are observed during batch normalization. However, the model demonstrates high validation accuracy, indicating robust generalization.

## Conclusion
The implementation of a CNN model with the Adam optimizer, batch normalization, dropout, and appropriate learning rate optimization results in superior performance in digit classification tasks. Utilizing a CNN architecture with three convolutional layers and early stopping further enhances accuracy and generalization capabilities.

For detailed findings and analyses, please refer to the complete report document.

---
**Note:** This README serves as a summary of the project. For comprehensive details and analysis, please review the complete report.
