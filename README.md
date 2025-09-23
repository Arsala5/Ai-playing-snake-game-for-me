# Snake Game AI

This project is a reinforcement learning agent that learns to play the classic Snake game using **Deep Q-Learning (DQN)**.

## How it works
- The game environment is built using **Pygame**.
- The agent uses a **neural network** (PyTorch) to decide moves.
- Training involves short-term and long-term memory updates to improve performance over time.
- A plotting utility shows the score progress as training continues.

## Project Structure
- `game.py` → Snake game logic and environment.
- `agent.py` → Reinforcement learning agent and training loop.
- `model.py` → Neural network and Q-learning trainer.
- `helper.py` → Plotting training results.

## Getting Started
1. Install dependencies:
   ```bash
   pip install torch pygame matplotlib
