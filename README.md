Feedforward Neural Network (FNN) – From Implementation to Training
Overview

This project focuses on building and training a Feedforward Neural Network (FNN) to better understand how neural networks learn from data. Rather than treating the network as a black box, the work emphasizes the underlying mechanics of forward propagation, loss computation, and parameter updates during training.

The notebook serves as a practical exploration of core deep learning concepts and is intended to strengthen foundational knowledge required for more advanced neural network architectures.

Problem Statement

Neural networks are widely used for prediction and classification tasks, but understanding how they function internally is critical for building reliable models. This project addresses the question:

How does a simple feedforward neural network learn from data, and how do its parameters evolve during training?

Approach
Data Handling

Input features and target labels are prepared and structured for supervised learning.

Data is passed through the network in batches during training to improve learning stability.

Network Design

A fully connected feedforward architecture is used.

Hidden layers apply non-linear activation functions to capture complex relationships.

The output layer produces predictions based on the learned representations.

Training Process

Forward propagation computes predictions from inputs.

A loss function measures the difference between predictions and true values.

Backpropagation calculates gradients of the loss with respect to network parameters.

Parameters are updated iteratively using a gradient-based optimizer.

Evaluation

Model performance is monitored across training epochs.

Changes in loss values are used to assess learning progress and convergence behavior.

Key Concepts Demonstrated

Feedforward neural network architecture

Forward and backward propagation

Loss functions and optimization

Learning rate effects on convergence

Difference between parameters and hyperparameters

Model generalization vs overfitting

Results and Observations

The network successfully learns patterns in the data as training progresses.

A steady decrease in loss indicates effective learning.

Model performance is sensitive to hyperparameter choices such as learning rate and network depth.

Even simple architectures can perform well when properly trained and tuned.

Tools and Environment

Language: Python

Libraries: NumPy, Matplotlib, PyTorch (or custom neural network logic as implemented)

Development Environment: Jupyter Notebook / VS Code

How to Run the Project

Clone the repository:

git clone https://github.com/your-username/fnn-lab.git


Install required dependencies:

pip install numpy matplotlib torch


Open and run the notebook:

jupyter notebook FNN_Lab.ipynb

What I Learned

How neural networks update weights through gradient descent

Why activation functions are essential for learning non-linear relationships

How training dynamics change with different hyperparameter choices

The importance of evaluating learning behavior, not just final accuracy

Possible Extensions

Adding a validation dataset for better generalization assessment

Comparing different activation functions and optimizers

Extending the network to multiple hidden layers

Applying the same architecture to a real-world dataset

Author

Chinenye Onyedika
Data Analytics Graduate | Machine Learning & Deep Learning Enthusiast
Windsor, Ontario, Canada
