# Least Misérables: Bomberman Game Agent

## Project Overview

The aim is to train an agent capable of real-time decision-making in the Bomberman game, competing against both trained and rule-based agents. Detailed report included in Documentation.pdf

## Key Components

### Game Setup

- **Grid:** 17x17 arena
- **Objects:** Walls, crates, bombs, agents, and coins

### Machine Learning Approaches

- **Imitation Learning:** Mimics expert strategies for safe exploration
- **Deep Q-Network (DQN):** Enhances strategic decision-making through environment interactions

### Features

- **Convolutional Features:** Effective for spatial understanding in the game
- **Linear Features:** Initially explored, later optimized for performance

### Models

- **Least_Ultimate_Agent:** Imitation-based model, strong at coin collection
- **Less_Ultimate_Agent:** DQN-enhanced, better at handling complex scenarios
- **Ultimate_Agent:** Combines models using ensemble techniques for improved stability

## Training Methodology

- **Scenario Tuning:** Iteratively introduces complexity to improve learning
- **Pipeline Training:** Uses imitation and DQN learning for robust model development

## Future Improvements

- Fine-tune model parameters and reward structures
- Optimize feature extraction for dynamic game states

## Getting Started

1. Clone the repository:
   git clone https://github.com/madham97/Least_Miserables.git
2. Install necessary dependencies as listed in requirements.txt.
3. Run training scripts to develop the Bomberman agent.
