# Snake Game AI

![Snake Game](https://img.shields.io/badge/Snake-Game-brightgreen)

A reinforcement learning-based AI to play the classic Snake game using a deep Q-network.

<p align="center">
  <img alt="GIF" width="300" src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3ZlOGhyNndjdDk3MW84MGdlenVxNXJ4cXU2MWgxdWUxaTc1MGduaiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l41JOTFaDuISTbge4/giphy.gif">
</p>

## Introduction

This project implements an AI agent that learns to play the Snake game using a deep Q-network (DQN). The agent is trained using reinforcement learning techniques and can achieve high scores by learning from its experiences.




## Features

- **Deep Q-Network**: Utilizes a neural network to approximate the Q-value function.
- **Experience Replay**: Stores past experiences to break correlation between consecutive samples.
- **Exploration vs Exploitation**: Balances between exploring new actions and exploiting known actions.
- **Visualization**: Plots the training progress and scores.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/snake-game-ai.git
    cd snake-game-ai
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. To train the AI agent, run:
    ```sh
    python agent.py
    ```

2. The training progress and scores will be plotted in real-time.

## Files

- [`agent.py`](agent.py): Contains the `Agent` class that implements the DQN and training logic.
- [`game.py`](game.py): Contains the `SnakeGameAI` class that implements the game mechanics.
- [`model.py`](model.py): Contains the neural network model (`Linear_QNet`) and the trainer (`QTrainer`).
- [`helper.py`](helper.py): Contains helper functions, including the `plot` function for visualizing training progress.
- `arial.ttf`: Font file used for rendering text in the game.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.