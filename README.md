# Foundations of DNN

## About Deep Learning

Deep Learning is a subset of machine learning that uses multi-layered neural networks to automatically learn patterns and representations from data. It powers applications like image recognition, natural language processing, forecasting, and generative modeling — forming the foundation of most modern AI systems.

## What This Repo Contains

This repository is a collection of foundational deep learning implementations, covering core architectures and concepts — from basic tensor operations and activation functions to ANNs, CNNs, RNNs, LSTMs, transfer learning, and GANs — built as part of my learning journey into AI research.

## Tech Stack

- Python 3.10
- TensorFlow / Keras
- Scikit-learn
- NumPy, Pandas, Matplotlib

## Datasets

Datasets used across these notebooks are not included in this repository due to size. All datasets can be downloaded from **Kaggle** — search for the relevant dataset name mentioned in each notebook before running it.

## Notebooks

- **DL_EDA_Preprocessing.ipynb** — Exploratory data analysis and preprocessing on a fraud detection dataset, covering missing value handling, encoding, scaling, and visualization of transaction patterns.

- **DL_TensorFlow_Basics.ipynb** — Introduction to TensorFlow tensors, covering scalars, vectors, matrices, and 3D tensors along with basic tensor operations like addition and matrix multiplication.

- **DL_ActivationFunctions.ipynb** — Implementation of common activation functions from scratch, including Step, Linear, Sigmoid, Tanh, ReLU, Leaky ReLU, and Softmax, with visual plots.

- **DL_Perceptron.ipynb** — A basic perceptron/ANN architecture example demonstrating input, hidden, and output layers with a simple neuron configuration.

- **DL_ANN.ipynb** — An Artificial Neural Network built with Keras Dense layers, compared against a Random Forest classifier for fraud detection classification.

- **DL_CNN_SVHN.ipynb** — A Convolutional Neural Network trained on the SVHN dataset to classify house-number digits from real-world street view images.

- **DL_CNN_Butterfly.ipynb** — A CNN built to classify butterfly species from images, using convolution and pooling layers with accuracy/loss visualization.

- **DL_RNN.ipynb** — A Recurrent Neural Network (SimpleRNN) used for sentiment analysis on IMDB movie reviews, classifying them as positive or negative.

- **DL_LSTM.ipynb** — An LSTM model used for time-series forecasting, predicting stock closing prices using historical TCS stock data.

- **DL_TransferLearning_VGG16.ipynb** — Transfer learning using a pretrained VGG16 model as a frozen feature extractor, fine-tuned for butterfly image classification.

- **DL_GAN.ipynb** — A Generative Adversarial Network with generator and discriminator networks trained to generate handwritten digit images from the MNIST dataset.

## Requirements

```bash
pip install tensorflow numpy pandas matplotlib scikit-learn scipy
```
