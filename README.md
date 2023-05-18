![python_badge](https://img.shields.io/badge/python--blue?style=flat&logo=python)
![python_badge](https://img.shields.io/badge/Tensorflow--blue?style=flat&logo=tensorflow)
![python_badge](https://img.shields.io/badge/Keras--blue?style=flat&logo=keras)
![python_badge](https://img.shields.io/badge/numpy--blue?style=flat&logo=numpy)
![python_badge](https://img.shields.io/badge/pandas--blue?style=flat&logo=pandas)
![python_badge](https://img.shields.io/badge/machine_learning_Algorithms--blue?style=flat&logo=thealgorithms)

# Academic_Deep_learning_Project
Real time fashion-mnist classification using convolutional Autoencoders.

Dataset- Fashion_Mnist.

Framework: Tensorflow and keras.

Implemented convolutional Autoencoder model and transfer learning to solve this problem. Autoencoders are used for reconstruction of the input image instances and it learns the parameters to train the fully connected classifier neural network. Also, autoencoders are used in image denoising and dimensionality reduction. The reason choosing of Autoencoders but not PCA is that PCA is primarily used for linear transformations but autoencoders are capable for building complex nonlinear functions.

Built a two deep neural network which includes two things. Firstly, a four-block convolutional autoencoder with following Maxpooling layer for each block. A classifier network with a fully connected three layered Dense networks for classifying Images. Secondly, VGG16 model is used with custom classifier network. The primary objective is to analyse both the models and their performance on real world fashion images.

The model is trained with 60,000 images and evaluated and tested with 10,000 images for measuring performance of the model. Both models are trained with different optimizers such as Adam, RMSprop, Adadelta and different learning rates. The best performance is achieved in autoencoder model with training accuracy 99.64% and test accuracy of 92.34%. The experimental analysis of results obtained from using different optimizers and learning rates 
