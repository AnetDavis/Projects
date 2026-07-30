# CartPole 

## Objective

This project implements the Proximal Policy Optimization (PPO) algorithm to train an intelligent agent for balancing a pole in the CartPole environment. The model learns through reinforcement learning by interacting with the environment and maximizing cumulative rewards.

## Environment

- **Environment:** CartPole-v1
- **Library:** Gymnasium
- **Learning Type:** Reinforcement Learning
- **Algorithm:** Proximal Policy Optimization (PPO)

## Project Workflow

### 1. Environment Setup
- Create the CartPole-v1 environment.
- Initialize the PPO agent.

### 2. Agent Training
- Train the agent over multiple timesteps.
- Learn an optimal policy through trial and error.

### 3. Model Saving
- Save the trained PPO model after training.
- Store training logs and performance metrics.

### 4. Model Evaluation
- Test the trained agent over multiple episodes.
- Calculate the average reward and overall performance.

### 5. Visualization
- Load the trained model.
- Render the environment to observe the agent balancing the pole.

## Technologies Used

- Python
- Gymnasium
- Stable-Baselines3
- NumPy
- Matplotlib

## How to Run

Train the PPO model:

```bash
python train.py
```

Evaluate the trained model:

```bash
python evaluate.py
```

Test the trained agent:

```bash
python test.py
```

## Results

The PPO agent successfully learns to balance the pole by maximizing rewards through continuous interaction with the environment. Training performance and evaluation metrics demonstrate the effectiveness of the reinforcement learning approach.

## Conclusion

This project demonstrates the application of Proximal Policy Optimization (PPO) in solving the CartPole reinforcement learning problem. The trained agent achieves stable performance and effectively balances the pole through learned policies.

## Author

**Name:** Anet Davis

**Registration Number:** 23BHI10146

**Application Number:** IN26011852

**Batch Number:** 1A

**Email ID:** anet.23bhi10146@vitbhopal.ac.in
