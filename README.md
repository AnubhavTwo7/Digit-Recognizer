# Handwritten Digit Recognizer

The Handwritten Digit Recognizer is an application that leverages the power of deep learning to identify human handwritten digits. Recognizing handwritten digits is a challenging task for computers due to the variations in individual handwriting styles. This project aims to provide an efficient solution to this problem using Convolutional Neural Networks (CNNs).

## Features

- **Handwritten Digit Recognition**: Capable of accurately recognizing digits from 0 to 9.
- **MNIST Dataset**: Utilizes the well-known MNIST dataset for training and testing the model.
- **Convolutional Neural Networks**: Implements a CNN to achieve high accuracy in digit recognition.
- **Interactive GUI**: Includes a graphical user interface that allows users to draw digits and receive immediate recognition results.

## Project Overview

### Dataset

The MNIST dataset is a large database of handwritten digits that is commonly used for training various image processing systems. The dataset contains 60,000 training images and 10,000 testing images.

### Model

The core of this project is a Convolutional Neural Network (CNN) designed to handle the intricacies of handwritten digits. CNNs are a class of deep neural networks, most commonly applied to analyzing visual imagery. The architecture of the CNN in this project is optimized for recognizing the unique features of handwritten digits.

### GUI

An interactive graphical user interface is built using Python libraries, allowing users to draw digits with their mouse. The drawn digit is then processed and recognized by the trained CNN model, displaying the result immediately.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/handwritten-digit-recognizer.git
   cd handwritten-digit-recognizer
