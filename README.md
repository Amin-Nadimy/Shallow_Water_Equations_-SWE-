# Shallow Water Equations Discretisation and Solution using Neural Networks

This repository presents a novel approach to the discretisation and solution of the Shallow Water Equations using finite difference (FD), finite volume (FV), and finite element methods (FE). Our method reformulates the discretised system of equations as a discrete convolution, analogous to a convolutional layer in a neural network, and solves it using Jacobi iteration.

## Key Features:
- **Platform-Agnostic Code**: Runs seamlessly on CPUs, GPUs, and AI-optimized processors.
- **Neural Network Integration**: Easily integrates with trained neural networks for sub-grid-scale models, surrogate models, or physics-informed approaches.
- **Accelerated Development**: Leverages machine-learning libraries to speed up model development.

## Applications:
- **Idealised Problems**: Validated against analytical solutions.
- **Laboratory Experiments**: Tested with controlled experimental data.
- **Real-World Test Case**: Applied to the 2005 Carlisle flood, demonstrating significant potential speed-ups with AI processors.

## Getting Started
To get started with the code, clone this repository and follow the instructions in the `examples` directory to run various test cases.

```sh
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY


## Example of Carlisle 2005 Flood Event Modeled with NN4PDEs
<img src="https://github.com/Amin-Nadimy/Shallow_Water_Equations_-SWE-/blob/main/SWE_2.gif" width="512" />
