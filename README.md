# Reinforcement Learning Model for Chrome Dino Game
This repository contains the implementation of a reinforcement learning (RL) model for training an agent to play the Chrome Dino game. The RL model is built using the DQN algorithm from the stable-baselines3 library. The trained model can learn to navigate and perform actions in the game environment to achieve high scores.

# Game Environment
The Chrome Dino game is a popular side-scrolling game where the player controls a running dinosaur to avoid obstacles and collect points. The RL model interacts with the game environment, observes the game state, and takes actions to maximize the cumulative reward.

# Dependencies
*Python 3.x  
*PyTorch  
*stable-baselines3  

# Installation

### Clone this repository:
git clone https://github.com/nikithkb/Dino-bot.git
cd Dino-bot

Download Chrome browser and go to chrome://dino

# Usage:

To train the RL model on the Chrome Dino game, follow these steps:

Set up the game environment by opening the Chrome Dino game on full screen in Chrome browser. Make sure the game environment is running.

Configure the training parameters in the Jupyter notebook under the "Parameters" section, such as the number of training steps, batch size, and learning rate.

# Run the training script:

Uncomment the first cell to finish installation of necessary packages for testing and training.
Note: The Chrome window must be kept in maximised mode as to capture position of the dino

# Results
The trained RL model achieves high scores and demonstrates the ability to navigate the Chrome Dino game environment effectively. It learns to avoid obstacles, collect points, and optimize its actions to maximize the cumulative reward.

# Acknowledgements
This project is based on the stable-baselines3 library, which provides the implementation of the DQN algorithm and RL training utilities.

# License
This project is licensed under the MIT License.

Feel free to provide any feedback or suggestions for improvement.

If you have any questions or run into any issues, please open an issue in the GitHub repository.

Happy gaming and happy RL training!
