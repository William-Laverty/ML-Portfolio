# 🚀 Machine Learning Portfolio

Explore a diverse range of machine learning projects, showcasing the profound capabilities and adaptability of ML from understanding student performance to facilitating the safe landing of spacecraft on lunar surfaces.

## 📘 Featured Projects

### 🎓 **Student Performance Predictor**
* **Objective**: Forecast students' final grades leveraging various academic and socio-economic indicators.
* **Technique**: Linear Regression
* **Dataset**: "student-mat.csv" from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Student+Performance), emphasizing performance in mathematics.
* **Highlights**: 
  * Command-line interface (CLI) for grade predictions.
  * Extensive data analysis and visual insights.
* **Dive Deeper**: Explore the [`gradePredictor.ipynb`](https://github.com/cgs-ist/student-grade-predictor-William-Laverty/blob/main/Linear%20Regression/gradePredictor.ipynb).

### 🌖 **Lunar Lander Performance Predictor**
* **Objective**: Equip a spacecraft with the capability to safely land on a lunar surface.
* **Technique**: Deep Q-Network (DQN)
* **Environment**: `LunarLander-v2` from OpenAI's gym, simulating lunar landing challenges.
* **Highlights**: 
  * Real-time spacecraft visualization.
  * DQN algorithm implementation.
  * Success metrics to evaluate performance.
* **Dive Deeper**: Navigate to [`LunarLander_Predictor.ipynb`](https://github.com/cgs-ist/student-grade-predictor-William-Laverty/blob/main/Reinforced%20Learning/LunarLander_Predictor.ipynb).

## 📖 **A Comprehensive Guide to Machine Learning**

For both newcomers and seasoned practitioners in the field of machine learning, this guide serves as an invaluable resource. Whether you're starting your journey or looking to solidify your understanding of various techniques, delve into this comprehensive guide.

* **Explore**: Familiarize yourself with core concepts, best practices, and nuanced approaches in machine learning.
* **Content**: The guide covers topics ranging from the foundational principles of machine learning to the advanced intricacies of specific algorithms.
* **Deep Dive**: Navigate to [A Guide to Machine Learning](https://github.com/William-Laverty/ML-Portfolio/blob/main/A%20Guide%20to%20Machine%20Learning.md) for a detailed exploration.

## 🔨 Set Up & Installation

Ensure you have the essential packages installed to seamlessly run the projects:

**Student Performance Predictor**:
```bash
pip install pandas numpy scikit-learn ipywidgets ttkthemes matplotlib.pyplot
```

**Lunar Lander Performance Predictor**:
```bash
brew install swig
pip install gym box2d-py tensorflow pygame numpy
```

## 🧑‍💻 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/William-Laverty/ML-Portfolio.git
```
2. Change directory to the desired project:
```bash
cd ML-Portfolio/<desired-project-directory>
```
3. Confirm all necessary packages are installed (refer to the Installation section).

4. Launch the respective Jupyter notebook for an in-depth exploration of the project.

## 🌐 Additional Resources

- [UCI Machine Learning Repository: Student Performance](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
- [OpenAI Gym](https://gym.openai.com)
