# Classifying MNIST data via Tensorflow Experiment Class

This notebook utilizes the Experiment class of the Tensorflow to automate the training and evaluation loops. 

## Notebook
The notebook is divided into 6 steps mentioned below:

1. Library Imports
2. Setting up the Dataset
3. Defining the Input Functions for Training and Evaluation
4. Setting up the Classifier
5. Setting up and running the Experiment
6. Evaluating our Model with Test Inputs

## Experiment
The Experiment loop runs for a default of 42969 steps and creates a checkpoint at this state for later use. The Experiment is set to learn
on the following performance measures:

- Accuracy
- Precision
- Recall
