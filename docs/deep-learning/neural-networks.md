# Neural Networks


## Introduction

A Neural Network is a computational model inspired by the structure and function of the human brain.

It consists of interconnected processing units called neurons that work together to learn patterns from data.


Neural networks are the fundamental building blocks of deep learning.


# Basic Structure


A simple neural network contains three main parts:


```
Input Layer
      |
      ↓
Hidden Layer(s)
      |
      ↓
Output Layer
```


## Input Layer

The input layer receives the original data.

Examples:


Image:

```
Pixel values
```


Weather prediction:

```
Temperature
Humidity
Wind speed
```


Text processing:

```
Word embeddings
```


The input layer passes information to the next layers.


# Hidden Layers


Hidden layers perform the actual learning process.

Each hidden layer transforms the input into more meaningful representations.


Example: Image Recognition


First layer:

```
Detect edges
```


Second layer:

```
Detect shapes
```


Third layer:

```
Detect objects
```


The deeper the network, the more complex patterns it can learn.


# Output Layer


The output layer produces the final result.


Examples:


Classification:

```
Cat = 95%
Dog = 5%
```


Regression:

```
Predicted temperature = 28°C
```


# Neurons


A neuron is the smallest processing unit of a neural network.


A neuron receives inputs, applies weights and bias, and produces an output.


Mathematical representation:


$$
y = f(wx+b)
$$


Where:


| Symbol | Meaning |
|---|---|
| x | Input |
| w | Weight |
| b | Bias |
| f | Activation function |
| y | Output |


# Weights


Weights determine how important an input is.

During training, the model adjusts weights to improve predictions.


Example:


If temperature strongly affects rainfall prediction:

```
Temperature weight = high
```


If another variable is less important:

```
Variable weight = low
```


# Bias


Bias allows neurons to adjust their output independently from the input.


It helps the model fit data better.


# Activation Function


An activation function decides whether a neuron should activate.

It introduces non-linearity into the network.


Without activation functions:

```
Deep network behaves like a simple linear model
```


Common activation functions:

- ReLU
- Sigmoid
- Tanh
- Softmax


# Forward Propagation


Forward propagation is the process of passing information from input to output.


Steps:

1. Input data enters network
2. Each neuron calculates output
3. Prediction is generated


Example:


```
Input Image

      ↓

Neural Network

      ↓

Prediction

      ↓

Cat
```


# Loss Function


The loss function measures how wrong the prediction is.


Example:


Actual value:

```
Cat
```


Prediction:

```
Dog
```


The loss will be high.


Training tries to minimize this loss.


# Backpropagation


Backpropagation is the learning mechanism of neural networks.


The model:

1. Makes a prediction
2. Calculates error
3. Sends error backward
4. Updates weights


Process:


```
Prediction

     ↓

Loss Calculation

     ↓

Error

     ↓

Weight Update
```


# Training Neural Networks


Training involves repeatedly:

- Feeding data
- Making predictions
- Calculating errors
- Updating weights


This process happens many times until the model improves.


# Types of Neural Networks


## Feed Forward Neural Network

Information moves only forward.

Applications:

- Classification
- Regression


## Convolutional Neural Network (CNN)

Designed for images.

Applications:

- Object detection
- Remote sensing


## Recurrent Neural Network (RNN)

Designed for sequential data.

Applications:

- Time series
- Text


## Transformer Networks

Modern architecture for language and vision.

Applications:

- ChatGPT
- Translation


# Applications


Neural networks are used in:


- Image recognition
- Weather prediction
- Fraud detection
- Medical diagnosis
- Autonomous vehicles
- Natural language processing


# Summary


Neural networks learn patterns by connecting many artificial neurons.

Important concepts:

- Layers
- Neurons
- Weights
- Bias
- Activation functions
- Forward propagation
- Backpropagation
- Training