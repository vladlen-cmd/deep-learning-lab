# AIML Lab Sem 7

# Deep Learning Lab (AIML) – Semester VII

## Student Information

**Name:** Vladlen Rebello
**PRN:** 23070521170
**Semester:** VII
**Section:** C

---

# About the Repository

This repository contains the practical experiments completed as part of the **Deep Learning Laboratory** for the Artificial Intelligence and Machine Learning (AIML) course. The experiments cover the fundamentals of deep learning, including Deep Feed Forward Networks (DFFN), Convolutional Neural Networks (CNN), Recurrent Neural Networks (RNN/LSTM), Transfer Learning, Autoencoders, and Generative Adversarial Networks (GANs).

The practicals were implemented using **Python**, **TensorFlow/Keras**, **Scikit-learn**, **NumPy**, **Pandas**, and **Matplotlib**. Each experiment follows a systematic workflow consisting of dataset preprocessing, model design, training, testing, evaluation, and visualization of results.

---

# Tools and Technologies

* Python
* TensorFlow
* Keras
* Scikit-learn
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook / Google Colab

---

# Experiments

## Experiment 1 – Introduction to Deep Learning Frameworks

### Theory

TensorFlow and Keras are widely used deep learning frameworks for designing, training, and deploying neural networks. A neural network consists of layers of neurons connected through weights. Activation functions introduce non-linearity, while optimizers adjust the weights during training to minimize the loss.

### Work Performed

* Installed TensorFlow and Keras
* Explored tensors and neural network layers
* Created a basic neural network
* Compiled and trained the model using different optimizers

---

## Experiment 2 – Housing Price Prediction using Deep Feed Forward Network

### Theory

A Deep Feed Forward Network (DFFN) is a neural network in which information flows from the input layer through hidden layers to the output layer without feedback connections. It is suitable for regression problems such as predicting house prices.

### Work Performed

* Loaded and preprocessed the housing dataset
* Normalized the features
* Built a DFFN with multiple hidden layers
* Trained and tested the model
* Evaluated performance using MAE, MSE, RMSE, and R² Score

---

## Experiment 3 – Classification using Deep Feed Forward Network

### Theory

Classification models predict discrete output classes. Deep Feed Forward Networks learn complex relationships between input features and output classes using fully connected layers and activation functions.

### Work Performed

* Loaded the Breast Cancer dataset
* Performed preprocessing and feature scaling
* Designed a DFFN classifier
* Trained and tested the model
* Evaluated results using Accuracy, Confusion Matrix, Precision, Recall, and F1-Score

---

## Experiment 4 – Regularization Techniques for Deep Learning

### Theory

Deep learning models may suffer from overfitting. Regularization techniques such as L1, L2, and Dropout improve generalization by reducing model complexity and preventing over-dependence on specific neurons.

### Work Performed

* Built a baseline neural network
* Applied L1 regularization
* Applied L2 regularization
* Implemented Dropout layers
* Compared the performance of all models

---

## Experiment 5 – Hyperparameter Tuning and Model Optimization

### Theory

Hyperparameters such as learning rate, batch size, number of layers, activation functions, and optimizers significantly affect model performance.

### Work Performed

* Experimented with Adam and SGD optimizers
* Modified learning rate
* Changed batch size
* Tested different activation functions
* Compared validation accuracy and loss

---

## Experiment 6 – Handwritten Digit Recognition using CNN

### Theory

Convolutional Neural Networks (CNNs) automatically learn image features using convolution and pooling layers. They are widely used for image classification tasks.

### Work Performed

* Loaded the MNIST dataset
* Built a CNN architecture
* Trained the model
* Evaluated classification accuracy
* Displayed digit predictions

---

## Experiment 7 – Dog Breed Classification using Transfer Learning

### Theory

Transfer Learning uses pretrained CNN models such as VGG16, ResNet, or MobileNet, allowing models to learn efficiently from smaller datasets while reducing training time.

### Work Performed

* Loaded a pretrained CNN model
* Fine-tuned the final layers
* Trained the classifier on dog breed images
* Evaluated model accuracy

---

## Experiment 8 – Stock Market Prediction using RNN/LSTM

### Theory

Recurrent Neural Networks (RNNs) and Long Short-Term Memory (LSTM) networks are designed for sequential data. They capture temporal dependencies in time-series datasets.

### Work Performed

* Loaded historical stock market data
* Prepared sequential input data
* Built an LSTM model
* Predicted stock prices
* Compared predicted and actual values

---

## Experiment 9 – Slot Filling using RNN

### Theory

Slot Filling is a sequence labeling task used in Natural Language Processing (NLP). RNN and LSTM models assign labels to each word in a sentence for spoken language understanding.

### Work Performed

* Performed text preprocessing
* Converted text into numerical sequences
* Built an LSTM-based sequence labeling model
* Evaluated prediction accuracy

---

## Experiment 10 – Credit Card Fraud Detection using Deep Learning

### Theory

Fraud detection is a binary classification problem involving highly imbalanced datasets. Deep neural networks can identify complex fraudulent transaction patterns.

### Work Performed

* Loaded and preprocessed transaction data
* Handled class imbalance
* Built a deep neural network
* Evaluated using Precision, Recall, F1-Score, and Accuracy

---

## Experiment 11 – Convolutional Autoencoder on MNIST

### Theory

An Autoencoder is an unsupervised neural network that compresses input data into a latent representation and reconstructs it. Convolutional Autoencoders are particularly effective for image compression and denoising.

### Work Performed

* Built encoder and decoder networks
* Trained the autoencoder
* Reconstructed handwritten digit images
* Compared original and reconstructed outputs

---

## Experiment 12 – Generative Adversarial Network (GAN)

### Theory

A GAN consists of two competing neural networks: the Generator, which creates synthetic images, and the Discriminator, which distinguishes real images from generated ones. Both networks improve through adversarial training.

### Work Performed

* Built Generator and Discriminator models
* Trained the GAN on handwritten digit images
* Generated synthetic digit images
* Visualized generated outputs after training

---

# Learning Outcomes

Through these experiments, I gained practical knowledge of:

* Deep Feed Forward Neural Networks
* Model preprocessing and feature engineering
* Regression and classification techniques
* Regularization methods
* Hyperparameter tuning
* Convolutional Neural Networks (CNN)
* Transfer Learning
* Recurrent Neural Networks (RNN/LSTM)
* Autoencoders
* Generative Adversarial Networks (GAN)
* Model evaluation using standard performance metrics

---

# Repository Structure

```
Deep-Learning-Lab/
│
├── Experiment-01/
├── Experiment-02/
├── Experiment-03/
├── Experiment-04/
├── Experiment-05/
├── Experiment-06/
├── Experiment-07/
├── Experiment-08/
├── Experiment-09/
├── Experiment-10/
├── Experiment-11/
├── Experiment-12/
└── README.md
```

---

# Author

**Vladlen Rebello**
**PRN:** 23070521170
**Semester VII – Section C**
