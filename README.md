# Chest-X-Ray-Classification

## Overview

This repository contains a deep learning model built to classify whether a person has pneumonia or is normal based on chest X-ray images. The model has been developed using a sequential algorithm and trained on a dataset of chest X-ray images of both pneumonia-positive and pneumonia-negative patients.

## Requirements

- Python (>=3.6)
- Keras (>=2.0)
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- cv2
- Seaborn


## Usage

To use the model for inference on new chest X-ray images, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Prepare your chest X-ray images for inference and place them in a separate folder.
4. Run the inference script `X ray image classification.ipynb`, providing the path to the folder containing your images:


The model will process the images and output predictions indicating whether the person has pneumonia or is normal.

## Model Architecture

The deep learning model is built using the Keras framework and follows a sequential architecture. It consists of several convolutional and pooling layers, followed by fully connected layers for classification. 


