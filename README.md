# Deep Q-Learning

This repository contains an implementation of Deep Q-Learning (DQL) applied to three different environments: Wumpus World, CartPole-v1, and LunarLander-v3.

## Project Overview

This project implements DQL algorithms to solve reinforcement learning tasks. Key achievements:
- CartPole-v1: Achieved average reward of 720.67 over 100 consecutive episodes (solving threshold: 470)
- Wumpus World: Consistent performance with rewards of 92.00
- LunarLander-v3: Demonstrated learning progress with rewards reaching 150-190

## Repository Structure
project/
├── notebooks/
│   └── dqn_implementation.ipynb
├── models/
│   ├── wumpus_model.pth
│   ├── cartpole_model.pth
│   └── lunar_model.pth
├── results/
│   └── training_results.json
├── report.pdf
└── README.md

## Dependencies

```python
pip install torch
pip install gymnasium
pip install numpy
pip install matplotlib
```
## Implementation Details

The implementation includes:
* Custom Wumpus World environment
* DQN with experience replay
* Target networks for stable learning 
* Customized hyperparameters for each environment

## Results

Each environment demonstrated different learning characteristics:
* Wumpus World: Stable learning with consistent performance
* CartPole-v1: Exceeded solving criteria significantly
* LunarLander-v3: Showed promising learning trajectory

For detailed analysis and results, please refer to report.pdf.

## Usage

1. Install dependencies
2. Run the Jupyter notebook
3. Models can be loaded from the saved .pth files
