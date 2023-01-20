# OFMC
The "Optimal Fashion MNIST Classification" project is a data science initiative aimed at improving the accuracy and efficiency of image classification on the Fashion-MNIST dataset using machine learning and deep learning techniques. To this end, the project employs a convolutional neural network (CNN) architecture for the classification process, and investigates various methods for optimizing the performance of this model. 

This notebook is a implementation of a convolutional neural network (CNN) model for classifying images of clothing items using the Fashion MNIST dataset. The model is built using TensorFlow's Keras API and trained on the dataset. The notebook also includes code for visualizing the results of the trained model and for evaluating its performance on a test set.
## Dependencies
- TensorFlow
- pandas
- numpy
- matplotlib
- sklearn

## Dataset
The dataset used in this notebook is the Fashion MNIST dataset, which contains images of clothing items along with their corresponding labels. The dataset can be downloaded from [here](https://github.com/zalandoresearch/fashion-mnist)

## Model
The model is a simple CNN model with the following architecture:
- 2D convolutional layer with 32 filters and a kernel size of 3
- Max pooling layer with a pool size of 2
- Dropout layer with a dropout rate of 0.2
- Flatten layer
- Dense layer with 32 units and a ReLU activation
- Dense output layer with 10 units and a softmax activation

## Training and Evaluation
The model is trained for 50 epochs using Adam optimizer and sparse categorical crossentropy as loss function. The training and validation accuracy is plotted after training. Model is then evaluated on the test set to get the test accuracy.

## Deployment
This model can be deployed on mobile devices,web or edge devices using TensorFlow Lite or TensorFlow.js. The model can also be saved and loaded for future use.
