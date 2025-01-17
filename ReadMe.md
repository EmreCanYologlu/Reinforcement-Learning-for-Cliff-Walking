# Reinforcement Learning Algorithms: Cliff Walking and Blackjack

## Overview

This project applies various reinforcement learning algorithms to solve:

1. **Cliff Walking Environment:**
   - Solved using **Policy Iteration** and **Value Iteration**.

2. **Gymnasium Blackjack Environment:**
   - Solved using **Q-Learning** and **SARSA (State-Action-Reward-State-Action)**.

The implementations are written in Python and consolidated into a single Jupyter Notebook for ease of experimentation and visualization.

---

## Features

### Cliff Walking
- **Environment:**
  - A gridworld problem where the agent must navigate from a start state to a goal state while avoiding cliffs.
  - Deterministic transitions.

- **Algorithms:**
  1. **Policy Iteration:** Iteratively evaluates and improves a policy until convergence.
  2. **Value Iteration:** Iteratively updates state values based on the Bellman Optimality Equation to derive the optimal policy.

- **Metrics:**
  - Total reward.
  - Number of iterations to convergence.
  - Visualization of the optimal policy.

### Gymnasium Blackjack
- **Environment:**
  - Simulates a simple card game where the agent must learn to maximize expected reward.
  - Stochastic transitions based on card draws.

- **Algorithms:**
  1. **Q-Learning:** Off-policy learning that updates Q-values using the maximum future reward.
  2. **SARSA:** On-policy learning that updates Q-values based on the next action chosen by the current policy.

- **Metrics:**
  - Win, loss, and draw rates.
  - Q-value heatmaps for state-action pairs.

---

## Installation and Setup

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd <project-directory>
   ```

2. **Open the Jupyter Notebook:**
   - Ensure Jupyter Notebook is installed.
   - Start the notebook server:
     ```bash
     jupyter notebook
     ```
   - Open the file `RL_Solutions.ipynb`.

---

## Usage

1. **Run the Notebook:**
   - Execute cells sequentially to:
     - Initialize environments.
     - Train algorithms.
     - Visualize results.

2. **Experiment with Parameters:**
   - Modify hyperparameters (e.g., learning rates, discount factors) directly in the notebook cells.

## Future Enhancements

1. **Parameter Tuning:** Automate hyperparameter optimization.
2. **Dynamic Visualization:** Interactive policy visualization.
3. **Additional Environments:** Extend the project to other Gymnasium environments.

---

## References

1. [Gymnasium Documentation](https://gymnasium.farama.org/)
2. [Reinforcement Learning: An Introduction](http://incompleteideas.net/book/the-book.html)

---

## Authors
- Names: Emre Can Yologlu


