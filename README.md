# 🚀 Machine Learning Projects Repository

Welcome to the repository containing a collection of machine learning projects. This repo demonstrates the power and versatility of machine learning across various domains, from predicting student performance to landing a spacecraft safely on a lunar surface.

## 📘 Projects

### 1. Student Performance Predictor

Predict student performance using the Linear Regression technique. The goal is to forecast the final grades of students based on various academic and socio-economic factors.

- **About**: This algorithm uses the "student-mat.csv" dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Student+Performance). The dataset contains information about student performance in mathematics.
- **Details**: Dive deeper into this project by exploring [`gradePredictor.ipynb`](https://github.com/cgs-ist/student-grade-predictor-William-Laverty/blob/main/Linear%20Regression/gradePredictor.ipynb).
- **Key Features**: Command-line interface (CLI) version for grade predictions, comprehensive data analysis, and visual insights.

### 2. Lunar Lander Performance Predictor

Train a spacecraft to safely land on a lunar surface using a Deep Q-Network (DQN).

- **About**: The project uses the `LunarLander-v2` environment from OpenAI's gym to simulate the challenges of landing a spacecraft on the moon.
- **Details**: Dive deeper into this project by exploring [`LunarLander_Predictor.ipynb`](https://github.com/cgs-ist/student-grade-predictor-William-Laverty/blob/main/Reinforced%20Learning/LunarLander_Predictor.ipynb).
- **Key Features**: Real-time spacecraft visualization, DQN implementation, and success metrics.

## 🔨 Installation

To ensure you can run the projects smoothly, make sure to install the necessary packages. Depending on the project you're interested in, you may need to install different sets of packages.

For **Student Performance Predictor**:

```bash
pip install pandas numpy scikit-learn ipywidgets ttkthemes numpy matplotlib.pyplot
```

For **Lunar Lander Performance Predictor**:

```bash
brew install swig
pip install gym box2d-py tensorflow pygame numpy
```

## 🧑‍💻 Usage

1. Clone the repository and navigate to the desired project directory.

```bash
git clone https://github.com/your-repo-link/MachineLearning-Projects.git
cd MachineLearning-Projects/<desired-project-directory>
```

2. Ensure you have the required packages installed for the chosen project (see the Installation section).

3. Run the respective Jupyter notebook to explore the project in-depth.

## 🌐 Links & References

- [UCI Machine Learning Repository: Student Performance](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
- [OpenAI Gym](https://gym.openai.com)
