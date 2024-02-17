# Pendulum Reinforcement Learning Project

![Python](https://img.shields.io/badge/python-v3.8-blue)
![PyTorch](https://img.shields.io/badge/pytorch-v1.10.0-orange)
![OpenAI Gym](https://img.shields.io/badge/openai--gym-v0.20.0-green)
![License](https://img.shields.io/badge/license-MIT-green)

This project focuses on implementing various reinforcement learning algorithms using PyTorch and OpenAI Gym environment for solving the Pendulum control problem. The implemented algorithms include Deep Q-Network (DQN), Enhanced DQN, Double DQN, and Soft Actor-Critic (SAC).

## Overview

The Pendulum control problem involves swinging a pendulum to the upright position using a motor. The goal is to learn a policy that maximizes the reward, typically defined as minimizing the angle and angular velocity of the pendulum.

## Implemented Algorithms

1. **Deep Q-Network (DQN)**: A standard Q-learning algorithm that approximates the Q-function using a neural network. It learns to map state-action pairs to their corresponding Q-values.

2. **Enhanced DQN**: An extension of the basic DQN algorithm with enhancements such as prioritized experience replay or dueling architectures to improve sample efficiency and stability.

3. **Double DQN**: A modification of the basic DQN algorithm that addresses the issue of overestimation of Q-values by decoupling the action selection and value estimation.

4. **Soft Actor-Critic (SAC)**: An off-policy actor-critic algorithm that combines the actor-critic approach with maximum entropy reinforcement learning, resulting in improved stability and sample efficiency.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/pendulum-rl-project.git
```

2. Navigate to the project directory:
```bash
cd pendulum-rl-project
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Environment
The Pendulum environment is provided by OpenAI Gym. It is a continuous control task where the goal is to swing up a pendulum and maintain it in the upright position.
