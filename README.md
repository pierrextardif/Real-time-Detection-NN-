# Real-time-Detection-NN-
Real-time Piano Detection - a paradigm for working with Pytorch->ONNX->Max/MSP.

# Real-Time detection of piano using Neural Networks

## Summary
We present an accessible paradigm for incorperating neural network model for interactive real-time applications.
As an example we show the ability to develop a simple detection model for piano notes and the classification of instrumets.
This paradigm is an open source that can be easily used by artists and researchers to combine NN models
for music and art applications.

## Method
The example is implementation as external objects in Max/MSP, and the workflow is as follow:

1. Generate a training set using the exteranl object traindyn~.mxo
2. Train using Pytorch.
3. Use the trained model with the external inferdyn~.mxo for inference.
