# 🎮 Reinforcement Learning Playground

This repository contains **two separate RL experiments** in one place:

1. **Tic-Tac-Toe RL Agent** — a gentle introduction where the agent learns not to play like a potato.
2. **Atari Pitfall RL Agent** — pure chaos mode, where the agent struggles against holes, ladders, and the meaning of existence.

Each experiment lives in its own notebook. Run them independently.

---

## 1) 🤝 Tic-Tac-Toe RL Agent

**Notebook:** `tic-tac-toe.ipynb`

This notebook trains an agent to play **Tic-Tac-Toe** using reinforcement learning.

### What Happens Here
- Agent initially places moves at random.
- Learns that losing feels bad.
- Eventually begins to block and win (sometimes intentionally).

### How to Run
1. Open the notebook in Jupyter / Colab.
2. Run cells in order.
3. Observe the transition from “huh???” to “oh, I get it!”

---

## 2) 🏃‍♂️💥 Atari Pitfall RL Agent

**Notebook:** `atari_pitfall.ipynb`

This notebook attempts to teach an agent how to play **Pitfall**, a game where falling into holes is less of a possibility and more of a destiny.

### What Happens Here
- Agent tries to move and jump.
- Agent discovers gravity the hard way.
- Training is slow but *sometimes* rewarding.

### How to Run
1. Make sure you have **gym + Atari environments** installed.
2. Preferably train using GPU (CPU training may take your entire lifespan).
3. Run notebook step-by-step.

---

## 🛠 Requirements

- Python
- Jupyter Notebook
- `gym` (with Atari dependencies for Pitfall)
- Torch / TensorFlow (depending on your implementation)
- **Patience** (mandatory)

---

## ⚠️ Disclaimer

If the agent performs well, you may celebrate.  
If it fails spectacularly — that’s **part of the show**.  
We learn. We fall. We fall again. And then maybe we jump correctly once.

---
