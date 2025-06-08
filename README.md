# 🧠 Tic Tac Toe Reinforcement Learning Agent (Q-Learning)

This project implements a reinforcement learning agent using **Q-learning** to play and master the classic game of Tic Tac Toe.

The agent learns optimal strategies through **self-play** against a random opponent, continuously improving by updating a Q-table using reward signals. A fully custom environment, training loop, and evaluation system have been built from scratch using Python.

---

## 🎮 Features

- ✅ Custom Tic Tac Toe environment using NumPy
- 🤖 Q-learning agent with ε-greedy policy and exploration decay
- 📊 Training progress visualization (win/loss/draw rates, epsilon decay)
- 🕹️ Interactive console gameplay — play against the trained agent
- 🧠 Reinforces understanding of RL fundamentals: states, actions, rewards, Bellman update

---

## 🧰 Tech Stack

- Python
- NumPy
- Matplotlib
- Google Colab / Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository or [open the Colab notebook](https://colab.research.google.com/drive/1J3RGmleMteft1ebchYRjIg4FtaN6PvxJ?authuser=0)
2. Run the training function:
   ```python
   agent = train_agent(episodes=20000)

📌 Author
Sibahle Sithole
Aspiring Data Scientist | Tech Educator
YouTube: Journey to Data
