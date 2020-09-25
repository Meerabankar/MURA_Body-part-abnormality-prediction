# MURA_Body-part-abnormality-prediction

The purpose of this project is to build a predictive model that will do work of radiologists i.e. to identify the abnormality of body parts from radiographs so that patients will get treated as early as they should be. Implemented a machine learning algorithm to identify abnormality of different body parts such as hands, shoulder, humerus, fingers, forearm, elbow, wrist from x-ray images image using functional API with CNN and dense neural network with cross entropy, activation functions RELU and sigmoid. The module is trained on different body part images with normal(no problem with the body part) and abnormal(some problem like bone scratch, joint tilt, etc) body part images and then used for predicting the abnormality with the probability. It is implemented using Python Keras/TensorFlow to identify abnormality of different body parts form x-ray images using CNN, ANN with functional API approach. Performance for different parameters was recorded while execution and accordingly modifications to Functional API were done to get the better accuracy. Model is evaluated using ROC and the accuracy of prediction Model is 86% accurate in predicting the abnormality. There are a few challenges to get better accuracy, more data is needed to get the better accuracy.
