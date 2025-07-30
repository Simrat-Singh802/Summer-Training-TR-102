Daily Diary – Day 26

Date: 30th July 2025

Topics Covered:

Forward Propagation

Backward Propagation

Gradient Descent

What I Did Today:
Today, I studied and understood the core mechanics of how neural networks learn by going through the processes of Forward Propagation, Backward Propagation, and Gradient Descent. These are fundamental to training an Artificial Neural Network effectively.

Part 1: Forward Propagation
What I Learned:
Forward propagation is the process of passing input data through the network from input layer → hidden layers → output layer.

Each neuron computes a weighted sum of its inputs and applies an activation function.

The final output is the network’s prediction based on current weights.

Key Points:
All activations are calculated layer by layer.

No learning happens during this step — just computation of outputs.

It helps evaluate the model’s current prediction before learning begins.

Part 2: Backward Propagation
What I Learned:
Backward propagation is the learning phase where the model updates its weights.

It starts by calculating the error (difference between predicted and actual values).

Then, the error is propagated backward through the network to adjust weights using partial derivatives (gradients).

Key Points:
Uses the chain rule of calculus to compute gradients of loss with respect to each weight.

Works layer by layer in reverse, from output to input.

The goal is to minimize the loss function.

Part 3: Gradient Descent
What I Learned:
Gradient Descent is the optimization algorithm used to update weights after backpropagation.

It minimizes the loss function by moving the weights in the direction of the negative gradient.

Gradient Descent Update Rule:
text
Copy
Edit
new_weight = old_weight - learning_rate × gradient
Key Concepts:
Learning Rate: Controls how big a step we take in each update.

Convergence: Model training continues until the loss is minimized or reaches a threshold.

Observations:
Forward and backward propagation together form the training loop of a neural network.

Choosing the right learning rate is critical — too high can overshoot, too low can make training very slow.

These steps repeat for many epochs to gradually improve the model's performance.

Tools & Resources Used:
Studied mathematical formulas and flow diagrams

Referred to videos and visual animations to understand backpropagation

