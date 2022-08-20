# Multi-class Classification

## Intro

Learning objectives:
  * Understand the classic MNIST problem.
  * Create a deep neural network that performs multi-class classification.
  * Tune the deep neural network.

Data set:
This MNIST dataset contains a lot of examples:

  * The MNIST training set contains 60,000 examples.
  * The MNIST test set contains 10,000 examples.

## Usage

### Running code cells
You must run code cells in order. In other words, you may only run a code cell once all the code cells preceding it have already been run.

To run a code cell:

1. Place the cursor anywhere inside the [ ] area at the top left of a code cell. The area inside the [ ] will display an arrow.
2. Click the arrow.
Alternatively, you may invoke Runtime->Run all. Note, though, that some of the code cells will fail because not all the coding is complete.

### Why did you see an error?
If a code cell returns an error when you run it, consider two common problems:

1. You didn't run all of the code cells preceding the current code cell.
2. If the code cell is labeled as a Task, then you haven't written the necessary code.

### Use the right version of TensorFlow
The following hidden code cell ensures that the Colab will run on TensorFlow 2.X, which is the most recent version of TensorFlow:
```python 
%tensorflow_version 2.x
```
## Definition

### 1. Build and train a model function
```create_model(my_learning_rate)```, which defines the model's topography.

```train_model(model, feature, label, epochs)```, uses input features and labels to train the model.

### 2. Plotting function

```plot_curve(epochs, hist, list_of_metrics)```,a plot curve.

## Document

Google LLC 2020

