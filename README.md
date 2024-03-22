# About

This repository contains code to work with the CIFAR-10 dataset. It consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The classes are: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

## Files

### `models.py`
The models.py file contains the definition of a neural network model architecture for solving the MNIST classification problem. It defines the structure of the neural network using PyTorch.

### `s8.ipynb`
The s5.ipynb notebook contains the main code to train and evaluate a model on the MNIST dataset. It imports the neural network architecture from models.py. The notebook then trains the model using the training data, evaluates its performance on the test data.

`1.Batch Normalization Model:` This model incorporates batch normalization layers to normalize the activations of each layer in the network.

`2.Group Normalization Model:` This model utilizes group normalization layers to normalize the activations of each layer in the network, with groups defined by the number of channels.

`3.Layer Normalization Model:` This model applies layer normalization to normalize the activations of each layer in the network.


## Usage
To use this code, follow these steps:

Clone the repository to your local machine:
 ```bash
git clone https://github.com/11kartheek/session-8.git
```
Open the s8.ipynb notebook in a Jupyter environment or any other compatible IDE.

Run the cells in the notebook sequentially to load the data, load the model architecture, train the model, and evaluate its performance.

Experiment with different hyperparameters and training strategies to improve performance if desired.

