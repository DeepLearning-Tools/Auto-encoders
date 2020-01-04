# Auto_encoders
A collection of tasks that provide an introduction to the working and implementation of auto-encoders.

# Introduction
Autoencoders are a type of ANNs which are used to learn efficient data representations in an unsupervised manner. The 
autoencoder consists of two components: an encoder and a decoder.The encoder uses raw-data(ex: images) as input and produces 
featues or representation as output. The decoder uses these features extracted from the encoder as input and reconstructs the 
original input raw-data. 

# RGB-to-Gray
Converting RGB images to grayscale is a simple task which can be done directly. However, for the purpose of learning the 
concepts of Autoencoders, I have implemented this task. In this project, the input RGB images are automatically converted to 
grayscale with the help of a simple network. This can also be performed the other way around (i.e, converting gray to RGB 
images) with several modifications to the network.

# Denoising images
Removing the noise from images is the first essential step in any computer vision tasks. With the help of a simple autoencoder 
network, we are able to achieve good results. There are several applications that needs more effective and complex autoencoders
to perform this task. Here, we see a very simple one. While training our network, we have to add noise to the samples and give 
these noisy images as input to our network. The output of our network is then compared with the good images for the purpose of
learning. 
