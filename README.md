# CNN-Image-Recognition

# Convolutional Neural Network (CNN) with Data Augmentation using TensorFlow

This repository contains a Convolutional Neural Network (CNN) implemented in TensorFlow for the CIFAR-10 dataset. The model is designed with increased complexity and includes data augmentation techniques for improved generalization.

## Training and Evaluation Results

The model is trained for 20 epochs with data augmentation. Here are the key results:

### Training Log

Epoch 1/20
1563/1563 [==============================] - 52s 31ms/step - loss: 1.5027 - accuracy: 0.4664 - val_loss: 2.0020 - val_accuracy: 0.3557 - lr: 0.0010
...
Epoch 20/20
1563/1563 [==============================] - 42s 27ms/step - loss: 0.4825 - accuracy: 0.8330 - val_loss: 0.5493 - val_accuracy: 0.8096 - lr: 2.4660e-04

bash
Copy code

### Test Accuracy

The final test accuracy achieved is 81.19%.

## Usage

1. Clone the repository:
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   
Install the required dependencies:
pip install tensorflow matplotlib

Run the training script.

Contributing
Feel free to contribute to the development of this project by opening issues or creating pull requests.
