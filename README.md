# Snake Game AI with Deep Q-Learning

This project implements an AI model that learns to play the classic Snake game using Deep Q-Learning. The AI agent learns the optimal strategy to avoid collisions, navigate towards the food, and maximize its score.

### Main Components

* **SnakeGameAI.py**: The *SnakeGameAI* class implements the Snake game, including game logic, state representation, and rendering. It provides a method for the agent to query the game's current state.

* **helper.py**: This module contains the *plot* function, which generates a graph of scores and mean scores over time, allowing you to assess the agent's performance throughout the training process.

* **model.py**: The *LinearQNet* class in this module represents the neural network architecture used by the agent to approximate the Q-values. It is implemented using PyTorch.

* **agent.py**: This module contains the *Agent* class, responsible for training the AI agent and choosing actions based on the current game state. The agent uses a memory buffer to store past experiences and train both short-term and long-term memory.

### Usage

Run the agent.py script to train the AI model and play the Snake game.

The script will train the AI agent using Deep Q-Learning and visualize its performance using a plot of scores and mean scores over time. If the agent achieves a new high score, the model will be saved for future use.

![Demo GIF](https://i.imgur.com/Hhw2HgX.gif)
