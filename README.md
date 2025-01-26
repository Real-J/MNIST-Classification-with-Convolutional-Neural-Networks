# MNIST Classification with Convolutional Neural Networks

This repository contains a Python script for building, training, and evaluating a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset using TensorFlow/Keras.

## Features
- Preprocessing of the MNIST dataset (normalization and reshaping)
- A CNN architecture with:
  - Two convolutional layers with ReLU activation
  - Max pooling layers
  - A fully connected layer with dropout for regularization
- Model compilation with the Adam optimizer and categorical cross-entropy loss
- Evaluation of the model on the test dataset
- Optional saving of the trained model

## Requirements
- Python 3.7 or higher
- TensorFlow 2.x

Install the required packages using pip:
```bash
pip install tensorflow
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/Real-J/mnist-cnn-classification.git
cd mnist-cnn-classification
```

2. Run the script:
```bash
python cnn.py
```

3. View the test accuracy in the output.

## Files
- `cnn_mnist_classification.py`: The main script containing the CNN implementation.
- `mnist_cnn_model.h5`: Saved model file (optional, generated after training).

## Results
After training for 10 epochs, the model achieves a test accuracy of approximately **99%**.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing
Feel free to open issues or submit pull requests to improve this repository.

## Acknowledgments
- [MNIST dataset](http://yann.lecun.com/exdb/mnist/)
- TensorFlow/Keras for providing a comprehensive framework for deep learning.

