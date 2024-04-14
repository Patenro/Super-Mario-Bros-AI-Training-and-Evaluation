# Super-Mario-Bros-AI-Training-and-Evaluation
This repository contains code for training an AI agent to play the Super Mario Bros game using reinforcement learning algorithms such as DQN, A2C, and PPO. It also includes evaluation of the trained models and testing of the best-performing model.
Sure, here's the README content in Markdown format:

## Dependencies

Make sure you have the following dependencies installed:

- `nes-py`
- `gym-super-mario-bros==7.3.0`
- `setuptools==65.5.0` (installing an older version to avoid conflicts)
- `gym==0.21.0`
- `gymnasium`
- `stable-baselines3[extra]==1.8.0`
- `sb3_contrib==1.8.0`
- `numpy`
- `opencv-python`
- `torch`
- `matplotlib`
- `pandas`
- `pytz`

You can install these dependencies using pip:

```bash
pip install nes-py gym-super-mario-bros==7.3.0 setuptools==65.5.0 "wheel<0.40.0" gym==0.21.0 gymnasium stable-baselines3[extra]==1.8.0 sb3_contrib==1.8.0 numpy opencv-python torch matplotlib pandas pytz
```

## Steps to Run the Code

1. Clone the repository to your local machine:

```bash
git clone https://github.com/Patenro/Super-Mario-Bros-AI-Training-and-Evaluation.git
```

2. Navigate to the cloned directory:

```bash
cd Super-Mario-Bros-AI-Training-and-Evaluation
```

3. Run the Python script:

```bash
python <script_name>.py
```

## Understanding the Code

- The code uses reinforcement learning algorithms provided by the `stable-baselines3` library to train an AI agent to play Super Mario Bros.
- It includes custom wrappers for preprocessing the game environment, custom reward shaping, and logging.
- The training process involves selecting an algorithm (DQN, A2C, or PPO), setting hyperparameters, training the model, and evaluating its performance.
- The trained models are saved, and their performance is evaluated using test episodes.

## Input Parameters

- **Check Frequency (default: 100000):** Specifies how often to check the model's performance during training.
- **Total Timesteps (default: 5000000):** Total number of timesteps for training the model.
- **Learning Rate (default: 0.0001):** Learning rate used by the optimizer during training.

## Output

- The code generates log files containing training and evaluation metrics, as well as reward vs. timesteps plots for visualization.
- Trained models are saved in separate directories based on the selected algorithm.

## Evaluation

- After training, the code evaluates the trained models using test episodes and logs the results.
- It also tests the best-performing model based on the highest reward achieved during training.

## Repository Structure

- `README.md`: Provides an overview of the code and instructions for running it.
- `<script_name>.py`: Python script containing the main code for training and evaluation.
- `logs/`: Directory containing log files generated during training.
- `DQN_agent_model/`, `A2C_agent_model/`, `PPO_agent_model/`: Directories containing saved models for each algorithm.
- `Reward vs Timesteps <algorithm>.png`: Plots visualizing reward vs. timesteps for each algorithm.

## Contributors

- Adeola Fagbenro
- Student ID: 27492286
- University of Lincoln

Feel free to contribute to this project by submitting bug fixes, feature enhancements, or new algorithms!
```

You can copy and paste this Markdown content into a `README.md` file in your GitHub repository. Let me know if you need further assistance!
