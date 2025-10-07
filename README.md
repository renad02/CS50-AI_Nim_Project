#  Nim Game AI — Q-Learning Project

This project implements an AI agent that learns to play the mathematical game Nim using **Q-learning, a reinforcement-learning algorithm**.

The AI trains by playing against itself thousands of times, gradually learning which moves lead to victory.

---

##  Game Rules
Nim starts with several piles of objects.

On each turn, a player removes one or more objects from a single pile.

The player who removes the last object wins.

---

## How It Works
- **State**: Current layout of piles.
- **Action**: Which pile to take from and how many objects to remove.
- **Reward**: +1 for winning, -1 for losing, 0 otherwise.
- **Learning**: The AI updates Q-values for each state-action pair and balances exploration vs. exploitation to improve over time.

---

##  Run the Project
```bash
python play.py
```
Then play against the trained AI directly in the terminal.

---

##  Concepts
- Reinforcement Learning
- Q-Learning
- Game Theory
- Self-Play Training

---


