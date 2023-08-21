# 🚀 Machine Learning: Lunar Lander Performance Predictor

Welcome to the **Machine Learning for Lunar Lander Performance Predictor**. This project utilizes a Deep Q-Network (DQN) to train an agent to land a spacecraft safely on a lunar surface. The predictor aims to maximize the reward during landing, ensuring the spacecraft lands upright and within the designated landing area.

The training utilizes the `LunarLander-v2` environment from OpenAI's gym. This environment simulates the physics and challenges of landing a spacecraft on the moon.

- [`LunarLander_Predictor.ipynb`](https://github.com/cgs-ist/student-grade-predictor-William-Laverty/blob/main/Reinforced%20Learning/LunarLander-QLearning.ipynb): This Jupyter Notebook provides the core implementation of the DQN algorithm, visualization of the spacecraft's performance, and other supporting utilities.

## 🎯 Project Overview

The Lunar Lander Performance Predictor aims to achieve the following:

1. **Environment Interaction**: The spacecraft interacts with its environment, receiving rewards or penalties based on its actions.
2. **Deep Q-Network (DQN) Implementation**: A neural network approximates the Q-values for the state-action pairs. This helps the agent determine the best possible action in a given state.
3. **Visualization**: The Pygame library provides a visual representation of the spacecraft's performance, showing its position, orientation, and landing success.
4. **Success Metric**: The model's success is measured based on the number of successful landings relative to the total number of episodes played.

## 🔨 Install the required packages

To ensure the project runs smoothly, the following packages are essential:

- **gym**  # Provides environments for reinforcement learning
- **box2d-py**  # Physics engine for gym
- **tensorflow**  # Machine learning framework
- **pygame**  # Enables game development and visualizations
- **numpy**  # Fundamental package for numerical computations

To install the required packages, execute the following command:

```bash
brew install swig
pip install gym box2d-py tensorflow pygame numpy
```

## 🧑‍💻 Usage

1. Clone the repository and navigate to the project directory.

```bash
git clone https://github.com/cgs-ist/student-grade-predictor-William-Laverty.git
cd reinforcedLearning
```

2. Ensure you have the required packages installed (see the Installation section).

3. Run the Jupyter notebook `"LunarLander_Predictor.ipynb"` to view the training process, model's performance, and interact with visualizations.

### 📚 References

Brockman, Greg et al. (2016). OpenAI Gym. [Link](https://gym.openai.com)
