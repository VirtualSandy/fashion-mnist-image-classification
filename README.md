# Fashion MNIST CNN Classifier
This project uses a Convolutional Neural Network (CNN) built using Keras to classify images from the Fashion MNIST dataset. This project includes a six-layer CNN for accurate image classification, as well as predictions on sample test images.

The repository provides a simple yet effective model that can later be adapted for more complex tasks, such as user profile image classification in marketing applications.

## Requirements
- **TensorFlow**
- **NumPy**
- **Matplotlib**

## How to Run
Install the required dependencies:

`pip install tensorflow numpy matplotlib`

**Run the Python script:**

`fashion_mnist_cnn.py`

The model will train and output predictions for two test images.

## Model Architecture
The CNN consists of six layers:

1. Three convolutional layers with ReLU activation
2. MaxPooling layers for dimensionality reduction
3. A Flatten layer to convert 2D feature maps into 1D vectors
4. A Dense layer with 64 units and ReLU activation
5. An output layer with softmax activation for classification

