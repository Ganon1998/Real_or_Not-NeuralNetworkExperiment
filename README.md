# Real_or_Not-NeuralNetworkExperiment
A project in Colab (Python, Keras, Tensorflow) that can tell the difference between a real or a fake face. This is an experiment to see if using a traditional neural network or a convolutional neural network is better for the task at hand. The goal of this project is to see if using pretrained, unsupervised learning models will let them better detect the differences between a real and a fake face. 

This project was created in an attempt to make a model that can detect if a face in a supposedly real social media account is using a real face or not. This facial detection might be used to better categorize social media accounts ran by a troll farm sas part of a foreign intelligence operation ofore example.

To test this, I made two neural networks: one Unsupervised using Dense layers and another that's a CNN and is Unsupervised. After these models were trained (fitting information in their respective Colab files) I put them to the test by giving them real and fake faces as well as their labels. The traditional neural network (with dense layers) seemed to perform better than the CNN.
