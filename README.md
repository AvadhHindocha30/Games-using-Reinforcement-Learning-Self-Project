# Games using Reinforcement Learning — Self Project

Small self-learning repo with toy RL problems.  
I trained a Blackjack agent with TD(λ) and built simple MDPs and bandit agents to compare exploration methods.

## Contents
- `Black-Jack Project.ipynb` — TD(λ) agent for Gymnasium Blackjack with ε-greedy, value surfaces, and policy heatmaps
- `Assignment0.py` — quick NumPy warm-up
- `Assignment1.ipynb` — Bandit Walk and Slippery Walk MDP construction
- `Assignment2.ipynb` — Frozen Lake with policy evaluation, policy improvement, value iteration, and policy iteration
- `Assignment3.ipynb` — Multi-Armed Bandits: ε-greedy, UCB, KL-UCB, Thompson Sampling, reward and regret plots

## Requirements
- Python 3.9+
- Install packages:
```bash
pip install numpy matplotlib seaborn gymnasium tqdm jupyter
# for Blackjack windowed demo
pip install pygame
