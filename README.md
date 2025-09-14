phase 1:

This project is an AI-based image segmentation implementation using PyTorch. It focuses on building and training three different neural network architectures from scratch: UNet, Attention UNet, and Residual Attention UNet. The goal is to perform image segmentation on the Massachusetts Roads Dataset, which involves identifying and labeling road pixels in aerial images.

Key components of the project include:

Data preparation and loading of images and corresponding masks.

Visualization of sample images and their masks.

Implementation of the three model architectures.

Training the models using appropriate hyperparameters.

Evaluation of the models using metrics such as accuracy, IoU (Intersection over Union), and Dice score.

The project leverages PyTorch for model building and training, and uses libraries like NumPy, PIL, and matplotlib for data handling and visualization. The dataset is downloaded via the Kaggle API, and the code includes steps for data preprocessing, augmentation, and splitting into training/validation sets.

The hyperparameters include image size (256x256), batch size (16), number of workers (2), learning rate (0.001), and number of epochs (15). The project also includes functionality to move the dataset to Google Drive for persistent storage when running on Colab.

Overall, this project demonstrates a complete pipeline for image segmentation using advanced CNN architectures with attention and residual mechanisms.



phase 2:

This project implements the **Soft Actor-Critic (SAC)** reinforcement learning algorithm for continuous control tasks. The code creates an AI agent that learns to master physics-based environments like the HalfCheetah robot simulation through a combination of:

- **Maximum entropy RL** - Balances exploration and exploitation by maximizing both reward and action entropy
- **Actor-Critic architecture** - Uses three neural networks (Actor, Double Critic, Value) for stable learning
- **Experience replay** - Stores and samples past experiences to break temporal correlations
- **Off-policy learning** - Decouples data collection from policy optimization

The agent successfully learns complex locomotion skills, progressing from random movements to coordinated running, demonstrating SAC's effectiveness for continuous control problems.

the videos of explaining the codes
https://drive.google.com/drive/folders/1jAhY3ymapHNzLj9JHrhRWFZ76LKOinmv?usp=sharing

Student names: Raya JanatAbadi - Baran Hosseini
Student numbers: 402105846 - 402170902
