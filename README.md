Autonomous Driving with Transformers and Convolutional Networks
=============================================================

This project demonstrates how to use Transformer and Convolutional Neural Network (CNN) architectures to train models for autonomous vehicle navigation. The objective is to predict the trajectory of the vehicle, using various input features like lane boundaries or images from the environment, and enabling the vehicle to drive using these predictions.

Overview
--------

This project focuses on three different approaches to drive an autonomous vehicle:

1. MLP Planner (Multi-Layer Perceptron): Predicts the vehicle's trajectory based on the lane boundaries.
2. Transformer Planner: Uses a Transformer model to predict the vehicle's trajectory by attending to the lane boundaries.
3. CNN Planner: Leverages Convolutional Neural Networks to predict the vehicle's trajectory directly from images.

The project uses the SuperTuxKart Drive Dataset to train the models, with a custom pipeline for processing and evaluating the predictions.
