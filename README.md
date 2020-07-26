# Computer Vision using Deep Learning
This project was created for the Master of Artificial Intelligence, KU Leuven. It is related to the semester project of the Master Course entitled: Computer Vision.
In this project, deep learning is introduced in various computer vision tasks. For the development needs, Python code, the OpenCV, and the Kera’s library are used.

## Overview

The dataset used to elaborate each of the tasks described in the current project, is the PASCAL VOC-2009 dataset. 
This dataset consists of colour images of various scenes with diﬀerent object classes (e.g. animal: bird, cat, ...; vehicle: aeroplane, bicycle, ...), totalling 20 classes. 
Finally, we retain five classes for the needs of our project (e.g. [aeroplane, car, chair, dog, bird] that yield 1.489 training and 1.470 validation images.

Tasks implemented:
* Initially, a comparison between linear Principal Components Analysis (PCA) and the non-linear (convolutional) auto-encoders is presented. 
* In a next section, various non-linear and convolutional autoencoder architectures are implemented. The different autoencoder architectures tested, 
contain either different number of coding variables, different number of convolutional layers and downsamples, or optimizers, cost and activation functions. 
Also, either very large models have been constructed or light-weight architectures, recording their performance. 
In each case, a comparison between an inital and the relevant reconstructed image is presented.
* In the next task, we use the output of the encoder of an autoencoder selected from the ones presented in the previous steps, directly for classiﬁcation, and train an end-to-end neural network. 
* Our ﬁnal goal is to translate the image classiﬁcation into a pixel-wise classiﬁcation task for segmentation purposes (semantic segmentation).

