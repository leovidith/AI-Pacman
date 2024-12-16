# Pac-Man Reinforcement Learning

## Project Objective:
To develop and train a Deep Q-Network (DQN)-based reinforcement learning agent capable of playing the Pac-Man game, maximizing scores through iterative sprints.

## Why Use Reinforcement Learning for Pac-Man?
Reinforcement Learning (RL) is ideal for game-based environments due to its focus on:
- Maximizing cumulative rewards through trial-and-error interactions.
- Handling dynamic, multi-step decision-making scenarios like Pac-Man.
- Adapting strategies for complex environments with varying challenges.


## Agile Sprint Overview:

#### **Sprint 1: Environment Setup and Requirements**
- Install required libraries and dependencies:
  - Gymnasium (for the `MsPacmanDeterministic-v0` environment).
  - PyTorch (for building the DQN model).
- Validate the gaming environment.
- Deliverable: Configured and validated game environment.

#### **Sprint 2: Model Architecture Design**
- Design the DQN with layers suitable for processing game state inputs.
- Implement Experience Replay for efficient training.
- Deliverable: Initial DQN model ready for training.

#### **Sprint 3: Training Pipeline Development**
- Implement epsilon-greedy exploration.
- Train the agent over 2000 episodes and log progress:
  - Average scores printed to console.
  - Checkpoint the model when achieving target performance (average score >= 500).
- Deliverable: Trained DQN model and training logs.

#### **Sprint 4: Gameplay Recording and Evaluation**
- Implement video recording to capture the agent’s gameplay.
- Validate the agent’s performance in solving the environment.
- Deliverable: Gameplay video (`video.mp4`) and performance evaluation report.

#### **Sprint 5: Deployment and Documentation**
- Deploy the trained model and gameplay viewer on the platform.
- Provide user-friendly documentation:
  - How to train the agent.
  - How to view and analyze gameplay.
- Deliverable: Deployed solution with complete user documentation.



### Features:
- **Deep Q-Network (DQN)**:
  - Neural network approximation for Q-value function.
  - Decision-making based on maximizing rewards.
- **Experience Replay**:
  - Stores and reuses past experiences to enhance learning.
- **Epsilon-Greedy Policy**:
  - Balances exploration of new actions with exploitation of learned strategies.
- **Gameplay Video Recording**:
  - Captures and displays the agent’s gameplay for analysis and visualization.



### Example Usage:

#### Training the Agent:
Run the following command to start training:

```bash
python train.py
```

#### Gameplay Recording:
After training, the gameplay video will be saved and displayed:

```bash
video.mp4
```

---

This Agile implementation provides a structured approach to delivering a high-performing reinforcement learning agent, ensuring technical robustness and user engagement.

