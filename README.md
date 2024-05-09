# Malaria-CNN-Model-
Malaria Cell Classification using Convolutional Neural Networks (CNNs)

This repository contains code for a Convolutional Neural Network model to classify blood smear images as uninfected or parasitized for malaria detection. The model is trained using the TensorFlow framework.

Dataset
The dataset used for training the model consists of approximately 27,558 cell images of parasitized and uninfected cells from thin blood smear slide images of segmented cells. The images are organized into two classes: 'Uninfected' and 'Parasitized'.

Link to dataset: "https://data.lhncbc.nlm.nih.gov/public/Malaria/cell_images.zip"

Training and Evaluation
The model is trained for 10 epochs on the training dataset, and its performance is evaluated on a separate validation dataset. During training, the model's accuracy and loss are monitored and these metrics are visualized using plots to assess the training progress and potential overfitting or underfitting.

Results
The trained model achieves a validation accuracy of approximately 0.9491925239562988% on the validation dataset.

Usage
To use the code:
1. Clone this repository: 'git clone https://github.com/champgirl/Malaria-CNN-Model-'
2. Navigate to the cloned directory: 'cd Malaria-CNN-Model-'
3. Install the required dependencies:
	import os
	import numpy as np
	import matplotlib.pyplot as plt
	import tensorflow
4. Run the 'malaria_cnn_model.ipynb' notebook to train and evaluate the model.


