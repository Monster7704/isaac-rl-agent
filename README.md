# isaac-rl-agent
# 🎮 Isaac RL Agent

A reinforcement learning agent for *The Binding of Isaac: Repentance* using **Repentogon**, **Lua sockets**, and **Stable Baselines3**.

🕹️ Trains an AI to control player movement, collect items, and survive enemies.

---

## 🧠 Features

- Real-time communication between Lua (game) and Python (AI)
- Custom Gym environment
- PPO-based RL agent using Stable Baselines3
- Supports Repentogon-modified Isaac

---

## 🛠️ Requirements

### Game
- The Binding of Isaac: Repentance (Steam)
- Repentogon installed: https://github.com/4ian/Repentogon 

### Python
```bash
pip install stable-baselines3 gym torch numpy
