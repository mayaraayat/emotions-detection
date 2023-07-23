# Emotion Classification Project

This project aims to classify images into different emotions using deep learning techniques. It utilizes the FastAI library for image classification tasks.

## Table of Contents

- [Project Description](#project-description)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Contributing](#contributing)


## Project Description

The Emotion Classification project utilizes the FastAI library to build an image classifier that can predict emotions in images. It uses a pre-trained convolutional neural network and fine-tunes it on a custom dataset of emotion-labeled images.

## Installation

1. Clone the project repository:
git clone https://github.com/mayaraayat/emotions-detection 
2. Install the required Python packages using pip:
pip install -r requirements.txt

## Usage

1. Prepare your dataset by organizing it into folders according to emotion labels:

dataset/
    angry/
        angry_image1.jpg
        angry_image2.jpg
        ...
    disgusted/
        disgusted_image1.jpg
        disgusted_image2.jpg
        ...
    ...

2. Update the train_path, test_path, and lr_choice variables in the code to point to the correct paths and values for your dataset and learning rate.
3. Run the script.

## Dataset

The dataset used in this project consists of images labeled with different emotions. It is organized into folders, with each folder representing a specific emotion category.

## Model Training 

The model training process involves fine-tuning a pre-trained convolutional neural network on the emotion-labeled images. The FastAI library is used to create a DataBlock and load the data. The fine_tune function is then used to train the model for a specified number of epochs.

## Evaluation

After training the model, the script evaluates the model's performance by predicting emotions on a separate test dataset. It calculates the accuracy of the predictions and displays a confusion matrix to visualize the results.

## Acknowledgments 

The sample dataset used in this project was sourced from Kaggle.
The code examples were adapted from various open-source tutorials and documentation.
