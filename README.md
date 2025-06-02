# 🧠 Human vs Minimax Agent

This project showcases a comparison between a **Human player** and an AI-driven **Minimax Agent** in a turn-based game environment (e.g., Tic-Tac-Toe, Connect Four, etc.). The aim is to demonstrate how decision-making using the Minimax algorithm leads to optimal or near-optimal play against human input.


## 🎮 Game Overview

- Turn-based game with clear win/loss/draw conditions.
- Human plays against an AI agent using the Minimax strategy.
- Input for the human player is provided via notebook input or GUI.

## 🧠 Minimax Agent

- Implements the **Minimax algorithm** to evaluate game states.
- Can be enhanced with:
  - **Alpha-Beta pruning** for performance.
  - Depth-limiting or evaluation functions for complex games.
- Always plays optimally (assuming perfect computation).

## 🧑 Human Player

- Makes manual moves via interface or notebook cell input.
- Competes against the AI in a fair, alternating format.

## 📊 Features

- Game board rendering (text or graphical).
- Turn tracking and move validation.
- End-of-game detection: win, loss, or draw.
- (Optional) Logging results of multiple rounds.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/human-vs-minimax.git
   cd human-vs-minimax
pip install -r requirements.txt

2. Install dependencies:
   ```bash
   jupyter notebook human_vs_minimax.ipynb
   
## Follow the prompts to play against the AI.

### 🧪 Example: Tic-Tac-Toe

| Player        | Strategy      | Win Rate |
|---------------|---------------|----------|
| Human         | Manual Input  | 25%      |
| Minimax Agent | Optimal Play  | 75%      |


Results may vary depending on player skill and game configuration.

## 📌 Requirements
- Python 3.8+
- Jupyter Notebook
- NumPy
- Matplotlib (optional)
- (Optional) Tkinter or Pygame for GUI
