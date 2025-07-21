# 🃏 Blackjack Strategy Simulator with Reinforcement Learning

This project explores various Blackjack strategies implemented using **Reinforcement Learning** (RL) techniques like **Q-learning** and **SARSA**. It also compares different strategic approaches in standard Blackjack and its popular variants, such as Spanish 21 and Late Surrender.

## 📁 Contents

The Jupyter Notebook `black_jack_Main (1).ipynb` includes the following simulations:

1. **Basic Strategy with Q-learning**  
   Learn the optimal policy using Q-learning based on standard Blackjack rules.

2. **Complete Point Count with Q-learning**  
   A card counting strategy integrated with Q-learning to adjust bets and actions dynamically.

3. **Complete Point Count with SARSA**  
   Similar to the above, but trained using SARSA (State-Action-Reward-State-Action), an on-policy learning algorithm.

4. **Spanish 21 (Basic vs Point Count)**  
   Simulates games with Spanish 21 rules and compares outcomes of the basic strategy and the point-counting strategy.

5. **Late Surrender (Basic vs Point Count)**  
   Incorporates the Late Surrender rule, analyzing strategic performance between basic and point-counting approaches.

## 🧠 Reinforcement Learning Overview

- **Q-learning** is a model-free RL algorithm that learns the value of action-state pairs and derives an optimal policy.
- **SARSA** learns similar value estimates but updates values using the action actually taken (on-policy).
- Both techniques improve the Blackjack strategy by learning from experience instead of relying solely on hardcoded rules.

## 📊 Key Features

- Simulates thousands of hands to train agents.
- Implements card counting (Hi-Lo or similar methods).
- Tracks agent performance over time.
- Compares win rates between strategies and rule variations.

## 🚀 How to Use

1. Clone the repo or download the `.ipynb` file.
2. Open in Jupyter Notebook or JupyterLab.
3. Run all cells in sequence or navigate to specific sections.
4. Adjust hyperparameters (learning rate, epsilon, episodes) for experimentation.

## 📌 Requirements

You may need the following Python packages:

```bash
pip install numpy matplotlib tqdm
