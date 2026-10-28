# Solving a Markov Decision Process: Value Iteration & Policy Iteration

Implementation of the two classic **dynamic-programming algorithms for MDPs**, **Value Iteration** and **Policy Iteration**, tested on a 3×3 **Grid World**. Built for the *Artificial Intelligence* course. It looks at how the optimal policy changes as the reward changes.

## What's inside
- **`GridWorld`:** the environment, with grid size, immediate rewards, the actions Up / Down / Left / Right, terminal states and transition dynamics
- **`Agent`:**
  - **Value Iteration:** applies Bellman optimality updates until the value function converges
  - **Policy extraction:** gets the greedy optimal policy from the converged values
  - **Policy Iteration:** alternates policy evaluation and policy improvement until the policy stops changing
- **Experiments:** several values of the living reward `r` with discount factor γ = 0.99. Both algorithms reach the same optimal policy, and the policy visibly changes with `r` (the agent either rushes to the exit or avoids it).

## Run it
Open `Value_iteration_and_Policy_Iteration.ipynb` in Jupyter or Google Colab. The only dependency is NumPy.

## Tech
Python · NumPy · reinforcement learning · MDPs · dynamic programming
