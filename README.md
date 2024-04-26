# Damped Mass-Spring System Modeling and Prediction using LSTM

## Introduction

This repository contains code for modeling the behavior of a damped mass-spring system and predicting its kinetic and potential energies using a Long Short-Term Memory (LSTM) neural network. The project utilizes the Euler method for simulation and PyTorch for building and training the LSTM model. After the initial training with manual hyperparameter tuning, a genetic algorithm is employed for further optimization.

## Features

- **Numerical Simulation**: Simulates the behavior of a damped mass-spring system and calculates positions, velocities, kinetic energies, and potential energies over time.
- **LSTM+FC Architecture**: Constructs an LSTM neural network with fully connected layers to predict kinetic and potential energies based on input sequences of positions and velocities.
- **Manual Hyperparameter Tuning**: Initially, hyperparameters are manually adjusted to optimize model performance through iterative trial-and-error.
- **Hyperparameter Optimization using Genetic Algorithm (PyGAD)**: Automates the optimization of hyperparameters using a genetic algorithm to further enhance model performance.
- **README Contents**: Includes a comprehensive README file to guide users on how to utilize and understand the project.

## Requirements

- Python 3.x
- PyTorch
- NumPy
- Matplotlib
- PyGAD

## Usage

1. Install the required libraries using `pip install -r requirements.txt`.
2. Run the `damped_spring_system.py` script to simulate the damped mass-spring system and train the LSTM model with manual hyperparameter tuning.
3. Optionally, run the `hyperparameter_optimization.py` script to optimize hyperparameters using PyGAD.
4. View the results and predictions through generated plots.

## File Structure

- `damped_spring_system.py`: Contains code for simulating the damped mass-spring system and training the LSTM model with manual hyperparameter tuning.
- `hyperparameter_optimization.py`: Implements hyperparameter optimization using PyGAD.
- `requirements.txt`: Lists all required Python libraries for easy installation.
- `README.md`: This file, containing project information, usage instructions, and other details.
- `LICENSE`: MIT License for open-source use.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project is inspired by the concepts of numerical simulation, neural networks, and optimization techniques.
- Credits to the authors and contributors of PyTorch, PyGAD, and other libraries used in this project.
