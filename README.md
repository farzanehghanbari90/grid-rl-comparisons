# Grid-World Reinforcement Learning Comparisons

This project implements and compares four standard RL algorithms—**Q-Learning**, **SARSA**, **DQN**, and **Double DQN**—in a simple 2D grid environment with obstacles and goal states.

## 📖 Overview

An agent starts at a designated **start** cell and must learn to navigate to the **goal** while avoiding obstacles.  
- **State space:** each grid cell  
- **Actions:** up, down, left, right  
- **Rewards:**  
  - Step cost: –1 per move  
  - Invalid move: –5  
  - Goal reached: +10  

The notebook walks through:
1. Environment setup  
2. Q-Learning implementation  
3. SARSA implementation  
4. DQN (Deep Q-Network)  
5. Double DQN  
6. Comparative analysis of learning curves and success rates  

## 🚀 Getting Started

1. Clone this repo  
2. Install dependencies (e.g. `pip install numpy matplotlib tensorflow`)  
3. Open `4_models_final.ipynb` in JupyterLab or VS Code  
4. Run each cell in order and inspect the plots  

## 📊 Results

At the end you’ll see reward-over-episode curves and a discussion of which algorithm is fastest to converge under different obstacle densities.

## 🤝 Contributing

Feel free to open issues or pull requests if you’d like to add new algorithms (e.g. **SARSA(λ)**, **Rainbow DQN**, etc.).

