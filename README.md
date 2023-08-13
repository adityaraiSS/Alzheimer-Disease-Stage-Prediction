# Alzheimer-Disease-Stage-Prediction

## Project Overview
This repository contains the implementation of a deep learning model to detect the stage of Alzheimer's disease using MRI images of the brain. The project focuses on utilizing state-of-the-art neural network architectures such as ResNet50, DenseNet121, and MobileNetV2 for accurate classification.

## Introduction
Alzheimer's disease is a progressive neurological disorder affecting memory, thinking, and behavior. Early detection of its stages is crucial for effective intervention and treatment. This project aims to build and train deep learning models that can classify MRI brain images into different stages of Alzheimer's disease.

## Data
The dataset used for this project consists of MRI images of brain scans categorized into four stages: MildDemented, ModerateDemented, NonDemented, and VeryMildDemented. The dataset is divided into training and testing sets for model development and evaluation.

## Installation
### Clone this repository:

bash
Copy code
git clone https://github.com/your-username/alzheimers-detection.git
cd alzheimers-detection
### Install the required Python packages:

Copy code
pip install -r requirements.txt

Usage
Prepare the data: Ensure that the MRI image dataset is appropriately organized in the /data directory.

## Run the model training scripts:

train_resnet.py: Trains the ResNet50 model.
train_densenet.py: Trains the DenseNet121 model.
train_mobilenet.py: Trains the MobileNetV2 model.
Evaluate the models: Use the trained models to evaluate their performance on the testing dataset.

## Contributing
Contributions to this project are welcome! If you find any issues or want to enhance the project, feel free to submit a pull request. For major changes, please open an issue to discuss your ideas first.
