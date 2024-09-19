# Detecting Arrythmia with Wavelet Transformation and Convolutional Neural Networks

In this project I studied Electrodiagrams (ECG), which can be used to monitor the proper functioning of the cardiovascular system.
I used machine learning and wavelet transformation to accurately classify real world datasets of normal and irregular heartbeats.

The main results are:
- Augmenting ECG data to help with the data imbalance arising from the relative scarcitiy of irregular heartbeats to normal heartbeats
- Training a Convolutional Neural Network (CNN) to classify the 5 types of heartbets with at least .95 area under the ROC curve for every class
- Applying Continuous Wavelet Transformation to the ECG signal to improve the predictive ability of the CNN architecture to at least .98 area under the ROC curve for every class
