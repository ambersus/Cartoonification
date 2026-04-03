# Cartoonization Project

This project focuses on converting real-life images and videos into cartoonized versions using computer vision and deep learning techniques.

## Directory Structure

*   **`train_code/`**: Contains the core machine learning implementation for training the cartoonization model.
    *   `train.py`: Main script to train the model.
    *   `pretrain.py`: Script for pre-training steps.
    *   `network.py`: Defines the neural network architecture.
    *   `loss.py`: Implements the objective loss functions.
    *   `layers.py`: Contains custom layers used in the network.
    *   `guided_filter.py`: Implements the guided filter algorithm, a crucial component for edge-preserving smoothing.
    *   `utils.py`: Various helper functions for data and image processing.
    *   `selective_search/`: Contains code for selective search, potentially for region proposal or object detection components.

*   **`testing/`**: Contains resources for evaluating and demonstrating the model.
    *   `rl imgs/`: Source, real-life (unprocessed) images for testing.
    *   `cartoonized_images/`: The output directories where cartoonized results are saved.
    *   Contains example cartoonized videos like "AVENGERS BAR SCENE [Cartoonized Version].mp4".

## Getting Started

1. Set up your environment with the necessary computer vision and deep learning dependencies.
2. Review `train_code/train.py` for training the model using your own dataset.
3. Test your trained model using the assets provided in the `testing/` folder or your own custom images.
