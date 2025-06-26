# 🐍 Snake Game AI

This is a simple yet interesting Snake Game built using Python.  
It has two modes:
- 🎮 A human-playable version using arrow keys
- 🤖 An AI version that learns to play the game using Reinforcement Learning (Deep Q-Learning with PyTorch)

## 📁 Project Structure

- `snake_game_human.py` → Play the game manually
- `agent.py` → Trains an AI to play automatically
- `model.py`, `helper.py`, `game.py` → Supporting files for the game and training
- `model/model.pth` → Trained AI model file

## 🛠 Requirements

You need Python installed. Then install dependencies:

```bash
pip install pygame torch matplotlib numpy
