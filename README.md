# CNN_CIFAR100
Convolutional neural network (CNN) is a class of deep neural network commonly used to analyze images. The objective of this project is to build a convolutional neural network model that can correctly recognize and classify colored images of objects into one of the 100 available classes for CIFAR-100 dataset. The recognition of images in this project has been done using transfer learning approach. The network built in this project uses the state-of-the-art EfficientNet-B0 which was trained on the popular, challenging and large ImageNet dataset. Transfer learning and the idea of intelligently scaling the network (carefully balancing the network's width, depth and resolution) helped in getting a good performance on this dataset. By just training the model for 11 epochs, the model managed to achieve an accuracy of 81 percent. The training of the model has been done on a GPU and the model has also been tested on some new random images to visualize the top 5 category predictions along with their probabilities.

DATA SOURCE
The dataset contains 3 folders - Meta, Train, Test.
Acknowledgements: This Dataset is taken from Kaggle/Cifar-10 and Cifar-100 datasets:
https://www.cs.toronto.edu/~kriz/cifar.html

Checkout full notebook for model training.
https://www.kaggle.com/mazhar01/cnn-cifar-100/output

The 100 classes in the CIFAR-100 are grouped into 20 superclasses. Each image comes with a 'fin' label (the class to which it belongs) and a 'coarse' label (the superclass to which it belongs)
