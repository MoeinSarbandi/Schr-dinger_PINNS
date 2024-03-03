# Physics-Informed Neural Networks for the Schrödinger Equation

## Introduction
This repository contains a Jupyter Notebook (`PINN_Schrödinger_Eq.ipynb`) dedicated to solving the Schrödinger Equation using Physics-Informed Neural Networks (PINNs). The Schrödinger Equation is central to quantum mechanics and describes how the quantum state of a physical system changes over time. This project leverages the power of PINNs to model and solve this complex equation, demonstrating an innovative intersection of physics and deep learning.

## Installation
Before running the notebook, ensure you have the following dependencies installed:

- `numpy`: For numerical operations.
- `matplotlib` and `seaborn`: For plotting and visualization.
- `torch`: For implementing and training the neural network model.

You can install all required dependencies by running:


## Comparison: Neural Network Without Physics in Loss Function vs. Using PINNs

To demonstrate the impact of incorporating physics into the loss function of neural networks, we present a comparison between two approaches:

- The first approach uses a conventional neural network that does not utilize physical laws in its loss function.
- The second approach leverages Physics-Informed Neural Networks (PINNs), which incorporate physical laws into the loss function to guide the learning process.

### Without Using Physics in Loss Function
Below is the result from a neural network trained without considering physical laws in its loss function. This approach might not fully capture the underlying physical phenomena, leading to less accurate or generalized solutions.

![Without Using Physics in Loss Function](path/to/your/fig1.png)

### Using PINNs
The figure below showcases the results from using Physics-Informed Neural Networks (PINNs). By integrating physical laws into the loss function, PINNs can achieve more accurate and physically plausible solutions, demonstrating the power of this approach.

![Using Physics-Informed Neural Networks (PINNs)](path/to/your/fig2.png)

This comparison clearly shows the advantages of incorporating physical laws into the training of neural networks, especially for tasks rooted in complex physical phenomena like solving the Schrödinger Equation.


## Contributing
Contributions to enhance this project are warmly welcomed, including but not limited to:
- Extensions or modifications to solve different equations using PINNs.
- Enhancements in data visualization for better interpretation of results.

