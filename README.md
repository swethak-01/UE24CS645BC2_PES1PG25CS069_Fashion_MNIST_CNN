# CNN Implementation on Fashion MNIST Dataset

## Repository Name

UE24CS645BC2_PES1PG25CS069_Fashion_MNIST_CNN

---

# Overview

This project focuses on implementing a Convolutional Neural Network (CNN) from scratch using Python and NumPy. The network is trained using the Fashion MNIST dataset for image classification tasks.

Instead of relying on high-level deep learning libraries for building the neural network, all important CNN operations were manually implemented to understand the internal functioning of convolutional neural networks.

The project includes:

* Convolution operation
* Max Pooling
* Forward propagation
* Backpropagation
* Fully Connected neural layer
* Activation functions
* CNN training and testing

---

# About the Dataset

Fashion MNIST is a benchmark dataset commonly used for image classification problems.

Dataset details:

* Total images: 70,000
* Training images: 60,000
* Testing images: 10,000
* Image size: 28 × 28 pixels
* Color format: Grayscale
* Number of classes: 10

Categories available in the dataset:

* T-shirt/top
* Trouser
* Pullover
* Dress
* Coat
* Sandal
* Shirt
* Sneaker
* Bag
* Ankle boot

---

# Tools and Libraries Used

The following technologies were used in this project:

* Python
* NumPy
* Matplotlib
* TensorFlow/Keras (dataset loading only)
* Google Colab

---

# CNN Components Implemented

## Convolution Layer

The convolution layer extracts important visual patterns from the image using learnable filters.

## ReLU Activation

ReLU introduces non-linearity into the model by converting negative values to zero.

## Max Pooling Layer

The pooling layer reduces the spatial dimensions of feature maps while preserving important information.

## Fully Connected Layer

The flattened feature maps are connected to dense neurons for final classification.

## Softmax Function

Softmax converts output scores into probability distributions for each class.

## Backpropagation

Gradient calculations are performed manually to update weights and improve prediction accuracy.

---

# Workflow of the Model

1. Load Fashion MNIST dataset
2. Normalize image pixel values
3. Apply convolution operation
4. Perform ReLU activation
5. Apply max pooling
6. Flatten pooled output
7. Pass through fully connected layer
8. Compute softmax probabilities
9. Calculate loss
10. Perform backpropagation
11. Update parameters
12. Evaluate model performance

---

# Running the Project

## Step 1

Open Google Colab.

## Step 2

Upload the notebook file or paste the code.

## Step 3

Run all cells in sequence.

---

# Expected Results

The CNN model outputs:

* Training loss
* Training accuracy
* Testing loss
* Testing accuracy
* Predicted labels for sample images

---

# Folder Structure

```text id="q2x0ln"
UE24CS645BC2_PES1PG25CS069_Fashion_MNIST_CNN/
│
├── README.md
├── Fashion_MNIST_CNN.ipynb
└── images/
```

---

# Academic Information

Student Name: Swetha K

USN: PES1PG25CS069

Subject: Deep Learning Techniques and Practice

---

# Summary

This assignment provided practical exposure to the implementation of CNNs from first principles. Building every layer manually helped in understanding feature extraction, pooling, activation functions, gradient computation, and neural network training in a detailed manner.
