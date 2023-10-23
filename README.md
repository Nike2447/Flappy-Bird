# Flappy Bird AI

This is a Python implementation of the classic game Flappy Bird with artificial intelligence controlling the bird's movements using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm.

## Prerequisites

Before running the code, make sure you have the following installed:

- Python: You can download it from [python.org](https://www.python.org/downloads/).

- Pygame: Install pygame using pip by running the following command in your terminal or command prompt:

    ```
    pip install pygame
    ```
- NEAT: Install neat using pip by running the following command in your terminal or command prompt:

      pip install neat-python
   

## Getting Started

1. Clone the repository or download the code files to your local machine.

2. Open a terminal or command prompt and navigate to the directory where the code is located.

3. Run the code by executing the following command:

    ```
    python flappy_bird_ai.py
    ```

## How to Play

The game will run with artificial intelligence controlling the bird. Your objective is to watch and enjoy the performance of the AI bird as it attempts to navigate through the pipes.

## Code Structure

- `flappy_bird_ai.py` is the main script that contains the game logic and AI implementation.

- `imgs` folder contains the images used for the game graphics.

- `config-feedforward.txt` is the configuration file for NEAT.

- The code consists of classes for `Bird`, `Pipe`, and `Base` to create game objects and manage their behaviors.

- The `main` function initializes the NEAT algorithm, evolves generations of AI birds, and runs the game loop.

- The game window is created using Pygame, and the game graphics are rendered in the `draw_window` function.

## NEAT Algorithm

This code utilizes the NEAT algorithm to evolve and train AI-controlled birds to play Flappy Bird. NEAT is a genetic algorithm that evolves neural networks to perform tasks.

- The AI birds are controlled by neural networks, which are evolved and improved over time to maximize their performance.

- The fitness of each bird is calculated based on its ability to navigate through the pipes, and better-performing birds are more likely to pass on their genetic information to the next generation.

## Acknowledgments

This code is based on the tutorial provided by [Tech With Tim](https://www.youtube.com/channel/UC4JX40jDee_tINbkjycV4Sg) on YouTube.

Enjoy watching the AI play Flappy Bird!
