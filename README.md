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
