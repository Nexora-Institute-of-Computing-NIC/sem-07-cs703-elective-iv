# CS703 — Elective IV: Reinforcement Learning — PLAN

**Semester:** 7 · **Credits:** 3 · **Level:** Advanced
**Theory:** 45 hrs · **Lab:** 15 hrs · **Tools:** Python, PyTorch, Gymnasium, Stable-Baselines3, matplotlib

## Syllabus

### Unit 1 — RL Foundations (9 lectures)
1. What RL is — learning from interaction
2. The agent-environment loop
3. States, actions, rewards, trajectories
4. Return and discounting
5. Policies — deterministic and stochastic
6. Value functions — V(s) and Q(s,a)
7. The Bellman equations
8. Exploration vs exploitation
9. RL vs supervised learning — what changes

### Unit 2 — Tabular Methods (9 lectures)
1. Multi-armed bandits — epsilon-greedy
2. UCB and Thompson sampling
3. Markov Decision Processes (MDPs)
4. Policy evaluation with dynamic programming
5. Policy improvement and iteration
6. Value iteration
7. Monte Carlo methods for prediction
8. Monte Carlo control
9. On-policy vs off-policy learning

### Unit 3 — Temporal Difference Learning (9 lectures)
1. TD(0) prediction
2. SARSA — on-policy TD control
3. Q-learning — off-policy TD control
4. Expected SARSA
5. Eligibility traces and TD(lambda)
6. n-step returns
7. Convergence guarantees
8. Exploration strategies in TD methods
9. When tabular methods fail — the curse of dimensionality

### Unit 4 — Deep Reinforcement Learning (9 lectures)
1. Function approximation — from tables to networks
2. Deep Q-Networks (DQN)
3. Experience replay and target networks
4. Double DQN and Dueling DQN
5. Policy gradient methods — REINFORCE
6. Actor-critic methods — A2C, A3C
7. Proximal Policy Optimisation (PPO)
8. Soft Actor-Critic (SAC) for continuous control
9. Model-based RL (overview)

### Unit 5 — Applications and Frontiers (9 lectures)
1. RL for games — Atari, AlphaGo, AlphaZero
2. RL for robotics and control
3. RL for recommendation systems
4. RL for resource scheduling and networking
5. RL for large language models — RLHF
6. Offline RL and batch RL
7. Multi-agent RL
8. Safety and alignment in RL
9. Evaluation and reproducibility

## Practical Labs (15)

1. Set up Gymnasium and run a random agent on CartPole
2. Implement epsilon-greedy bandit and compare to UCB
3. Value iteration on a small grid world
4. Monte Carlo control on FrozenLake
5. SARSA and Q-learning on the same environment — compare
6. Eligibility traces — TD(lambda) on a small MDP
7. DQN from scratch on CartPole
8. Double DQN — measure improvement
9. REINFORCE on CartPole
10. A2C with Stable-Baselines3
11. PPO on LunarLander
12. SAC on a continuous control task (Pendulum)
13. Train an agent on a custom OpenAI Gym environment
14. RLHF exercise — preference modelling on a toy task
15. Final project — a trained agent with evaluation report

## Assignments

1. MDP formulation — model a real problem as an MDP
2. Tabular methods — implement and compare three algorithms
3. DQN report — training curves, hyperparameters, failures
4. Policy gradient vs value-based — comparison report
5. Final project — a complete RL application with writeup
