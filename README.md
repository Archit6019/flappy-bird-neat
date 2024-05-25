# Flappy Bird AI with NEAT

This project implements an AI to play the Flappy Bird game using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm. The goal is to evolve neural networks that can successfully navigate through the game by avoiding pipes and scoring points.

## Installation
To install and run this project, follow these steps:

1. Clone the repository

```bash
git clone https://github.com/yourusername/flappy-bird-neat.git
cd flappy-bird-neat
```

2. Create a virtual environment and activate it:

```bash
python -m venv venv
venv\Scripts\activate
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage
To start training the AI to play Flappy Bird, simply run the main script:

```bash
python main.py
```

## Configuration
The behavior of the NEAT algorithm and the Flappy Bird game can be customized using the config-feedforward.txt file. Key parameters include:

1. Population size: Number of networks in each generation.
2. Fitness threshold: The fitness level required to consider the task solved.
3. Activation function: The activation function used in neural networks.
4. Number of hidden nodes: Initial number of hidden nodes in networks.

