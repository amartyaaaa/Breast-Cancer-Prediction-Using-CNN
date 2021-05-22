# Breast-Cancer-Prediction-Using-CNN
The challenge for this project was to build an algorithm to automatically identify whether a patient is suffering from breast cancer or not by looking at biopsy images. The algorithm had to be extremely accurate because lives of people is at stake.
CNN Architecture
Input:
A Matrix of pixel values in the shape of [WIDTH, HEIGHT, CHANNELS]. Let’s assume that our input is [32x32x3].
Convolution:
The purpose of this layer is to receive a feature map. Usually, we start with low number of filters for low-level feature detection. The deeper we go into the CNN, the more filters we use to detect high-level features. Feature detection is based on ‘scanning’ the input with the filter of a given size and applying matrix computations in order to derive a feature map.
The goal of this layer is to provide spatial variance, which simply means that the system will be capable of recognizing an object even when its appearance varies in some way. Pooling layer will perform a downsampling operation along the spatial dimensions (width, height), resulting in output such as [16x16x12] for pooling_size=(2, 2).
This project is basically used to determine if a certain cell is harmful to the body by being a cancer cell or if it’s harmless by being a malignant cell. We are using python language to write a code by the use of pre-set machine learning libraries to train a large amount of entries and then taking random entries and see if our algorithm is able to determine if a cell is harmful or harmless. It’s a basic application that is used in the medical industry and has a lot of scope for higher advancements in the future.

Methodology:
Deep learning CNN models to train and test, each input image will pass it through a series of convolution layers with filters (Kernels), Pooling, fully connected layers (FC) and apply sigmoid function to classify an object with probabilistic values between 0 and 1.
The model has been developed for two conditions, first when the dataset includes numerical values of images which are scaled to classify an image as benign or malignant.The model uses CNN architecture to predict the model accuracy.
The second condition is when the model is trained using training set consisiting of images which are benign and malignant. The model's accuracy is determined by deploying it on test set and predicting tha accuracy and loss.
