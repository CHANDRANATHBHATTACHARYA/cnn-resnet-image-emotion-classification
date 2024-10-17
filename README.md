# Fashion MNIST Classification with CNN and Emotion Detection with ResNet

This repository contains two machine learning tasks: classifying the Fashion MNIST dataset using Convolutional Neural Networks (CNN) and performing Emotion Detection using a ResNet architecture. Both tasks are part of an advanced machine learning assignment.

## Project Structure

- **AML_ASSIGNMENT_1.ipynb**: Jupyter Notebook containing the implementation of both the CNN for Fashion MNIST classification and the ResNet model for Emotion Detection.
- **Dataset**: 
  - **Fashion MNIST**: A dataset of 70,000 grayscale images of clothing items, used for the CNN task.
  - **Emotion Detection Dataset**: A custom dataset containing labeled facial images used to train and test the ResNet model.

## Model Details

### Task 1: Fashion MNIST Classification
- **Architecture**: The CNN model consists of multiple convolutional layers followed by pooling layers and fully connected layers.
- **Training**: The model is trained on the Fashion MNIST dataset, achieving high accuracy for image classification.

### Task 2: Emotion Detection with ResNet
- **Architecture**: A deep Residual Neural Network (ResNet) was implemented to detect facial emotions from images. The model utilizes skip connections to improve training efficiency and model accuracy.
- **Training**: The ResNet model is trained on a dataset of facial expressions and evaluated for its ability to correctly classify different emotions.

## Requirements

- Python 3.x
- TensorFlow or PyTorch (depending on the implementation)
- Jupyter Notebook

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cnn-resnet-emotion-detection.git
