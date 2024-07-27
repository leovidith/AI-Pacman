# Pac-Man Reinforcement Learning

This project demonstrates a reinforcement learning (RL) agent playing the Pac-Man game using a Deep Q-Network (DQN). The agent is trained to maximize its score in the game environment `MsPacmanDeterministic-v0` provided by OpenAI's Gym.

## Features

- **Deep Q-Network (DQN)**: The agent uses a neural network to approximate the Q-value function.
- **Experience Replay**: Stores and samples past experiences to improve learning stability.
- **Epsilon-Greedy Policy**: Balances exploration and exploitation during training.
- **Video Recording**: Captures and displays the agent’s gameplay.

## Requirements

- Python 3.x
- PyTorch
- Gymnasium
- Additional libraries

You can install the required packages using the following commands:

```bash
pip install gymnasium
pip install "gymnasium[atari, accept-rom-license]"
apt-get install -y swig
pip install gymnasium[box2d]
```
Usage
Run the training script:

Execute the following command to start training the DQN agent:

```bash
python train.py
```

Training Details:

The agent will be trained over 2000 episodes.
The training progress, including average scores, will be printed to the console.
The agent will save the trained model to checkpoint.pth once it solves the environment (average score >= 500.0).
View the Agent’s Gameplay:

After training, the agent’s gameplay video will be saved as video.mp4 and displayed in the notebook.
