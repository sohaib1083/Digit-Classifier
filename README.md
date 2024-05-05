# Pygame Handwritten Digit Recognizer

This project is a simple handwritten digit recognition program built using Pygame and a neural network model trained on the MNIST dataset.

## Introduction

The goal of this project is to provide a fun and interactive way to recognize handwritten digits using Pygame. Users can draw digits on the screen, and the program will predict the digit using the trained neural network model.

## Features

- Allows users to draw digits using the mouse.
- Real-time prediction of the drawn digit.
- Simple and intuitive user interface.

## Getting Started

### Prerequisites

Before running the program, make sure you have the following dependencies installed:

- Python (version 3.x)
- Pygame
- numpy
- pandas

You can install the dependencies using pip:


### Installation

1. Clone the repository to your local machine:



2. Navigate to the project directory:


3. Run the program:


## How to Use

1. Launch the program by running `draw.py`.
2. Use the mouse to draw a digit on the screen.
3. After releasing the mouse, the program will predict the drawn digit and display the result on the screen.

## Model Architecture

The neural network model used for digit recognition is a simple feedforward neural network implemented from scratch. The model consists of an input layer, one or more hidden layers, and an output layer. Each layer is densely connected to the next layer, and ReLU activation functions are used for the hidden layers, while the output layer uses softmax activation for multi-class classification.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was inspired by the MNIST dataset and Pygame tutorials.
- Special thanks to the developers of Pygame and the creators of the MNIST dataset.
