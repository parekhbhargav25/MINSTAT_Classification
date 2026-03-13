# MNIST Handwritten Digit Classification

This repository contains a Jupyter notebook implementing a simple neural network for classifying handwritten digits from the MNIST dataset using TensorFlow and Keras.

## Description

The MNIST dataset consists of 70,000 grayscale images of handwritten digits (0-9), each 28x28 pixels. This project demonstrates a basic machine learning workflow:

- Data loading and preprocessing
- Building and training a neural network
- Model evaluation and prediction
- Visualization of results

## Requirements

- Python 3.7+
- TensorFlow 2.x
- NumPy
- Matplotlib

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/mnist-classification.git
   cd mnist-classification
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook MINIST.ipynb
   ```

2. Run all cells in order. The notebook will:
   - Install required packages (if running in Colab)
   - Load and preprocess the MNIST data
   - Build and train a neural network
   - Evaluate the model
   - Make predictions on test images

## Model Architecture

- **Input Layer**: Flatten layer (28x28 → 784)
- **Hidden Layer**: Dense layer with 128 neurons, ReLU activation
- **Output Layer**: Dense layer with 10 neurons, softmax activation

## Results

The model typically achieves 97-98% accuracy on the test set after 50 epochs of training.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Feel free to submit issues and enhancement requests!