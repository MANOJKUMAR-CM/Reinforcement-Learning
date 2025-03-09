# 🚀 Reinforcement Learning (DA6400)  

This repository contains implementations of various reinforcement learning algorithms as part of the **DA6400** course at **IIT Madras**, instructed by **Prof. Balaraman Ravindran**. The implementations are developed as part of tutorial exercises to understand and analyze reinforcement learning techniques.

---

## 📌 Repository Highlights  

🔹 **Course:** DA6400 - Reinforcement Learning  
🔹 **Instructor:** Prof. Balaraman Ravindran  
🔹 **Focus:** Implementation of RL algorithms & experimental analysis  
🔹 **Status:** Ongoing updates with new algorithms 🚀  

---

## 📂 Repository Structure  

###  **Tutorial 1: Multi-Armed Bandit Algorithms**  
The first tutorial explores the **Bandit Problem**, implementing and analyzing different action-selection strategies:  

- ✅ **Random Policy**  
- ✅ **Epsilon-Greedy Algorithm**  
- ✅ **Softmax Exploration**  
- ✅ **Upper Confidence Bound (UCB)**  

📊 Comparative analysis of these algorithms is conducted to evaluate their performance in different settings.

### **Tutorial 2: MENACE - A Tic-Tac-Toe Learning System**  
The second tutorial focuses on **MENACE (Matchbox Educable Noughts And Crosses Engine)**, a physical reinforcement learning system designed by **Donald Michie** to play Tic-Tac-Toe.  

- ✅ **Understanding MENACE's Box-based Learning Approach**  
- ✅ **Implementation of MENACE in Python**  
- ✅ **Training MENACE to Improve Gameplay**  
- ✅ **Analysis of MENACE's Learning over Multiple Rounds**  

📈 This tutorial demonstrates how reinforcement learning principles can be applied even without traditional programming.  

###  **Tutorial 3: Value Iteration & Policy Iteration**  
The third tutorial implements **Value Iteration and Policy Iteration** on a standard grid world environment. The grid world consists of **121 cells (11 x 11)**, where the agent can move deterministically in four directions (**up, down, left, right**).

#### **Markov Decision Process (MDP) Setup:**
- **States (S):** 121 (11 x 11 grid)
- **Actions (A):** 4 (up, down, left, right)
- **Transition Probability (P):** Deterministic
- **Reward Function (R):** -1 at every step
- **Discount Factor (γ):** 0.9

The objective is to find the optimal policy using:
- ✅ **Value Iteration**
- ✅ **Policy Iteration**

📊 The results include visualizing the convergence of values and optimal policies in the grid world.

###  **Tutorial 4: SARSA & Q-Learning**  
The fourth tutorial implements **SARSA and Q-Learning** on a more challenging grid world environment with **stochasticity**.

#### **Environment Details:**  
- The agent can move using one of four actions: **UP, DOWN, LEFT, RIGHT**.  
- The goal is to reach a **predefined goal position** from a **randomly assigned starting position**.  
- If an action would take the agent off the grid, the agent remains in the same position.  
- The environment is a **17 × 23 grid**.  
- The reward for each cell is **negative of the value in that position** (except the goal cell).  
- **Goal reward is set to +100**.  
- **Maximum episode length** is **10,000 steps**.

#### **Adding Stochasticity:**
- With **20% probability**, the agent **takes a random action** (which may be different from the intended action).  
- A **westerly wind effect** exists, meaning that **with 50% probability**, the agent **moves an extra step to the right** after every action.  

The objective is to compare:
- ✅ **SARSA (On-Policy TD Control)**  
- ✅ **Q-Learning (Off-Policy TD Control)**  

📊 The results include analyzing the effect of **stochasticity, exploration strategies, and policy convergence**.

---

## 🔮 Future Updates  

🔜 **Temporal Difference Learning**  
🔜 **Monte Carlo Methods**  
🔜 **Deep Reinforcement Learning**  

Stay tuned for upcoming implementations and insights! 🎯  

---

## 📧 Contact  

If you have questions, suggestions, or just want to connect, feel free to reach out!  

- **Name**: Manoj Kumar.CM  
- **Email**: [manoj.kumar@dsai.iitm.ac.in]  
- **GitHub Profile**: [Manoj Kumar C M](https://github.com/MANOJKUMAR-CM)  

Happy coding! 🚀
