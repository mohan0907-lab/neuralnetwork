# FLOWER RECOGNITION USING CONVOLUTIONAL NEURAL NETWORK (CNN) 
Overview
This repository contains a Jupyter Notebook implementation of a flower recognition model using TensorFlow and Keras. The model is trained to classify images of flowers into 5 categories: daisy, dandelion, rose, sunflower, and tulip.

Features
Data preprocessing with TensorFlow's ImageDataGenerator

Convolutional Neural Network (CNN) architecture

Model training and evaluation

Visualization of training results

Flower classification on new images
Requirements
To run this notebook, you'll need:

Python 3.x

Jupyter Notebook

TensorFlow 2.x

Keras

NumPy

Matplotlib

OpenCV (for image processing)
Installation
Clone this repository:

bash
Copy
git clone https://github.com/yourusername/flower-recognition-model.git
cd flower-recognition-model
Install the required packages:

bash
Copy
pip install -r requirements.txt
Dataset
The model uses a dataset of 4,317 flower images divided into 5 classes:

Daisy: 764 images

Dandelion: 1,052 images

Rose: 784 images

Sunflower: 733 images

Tulip: 984 images
Usage
Open the Jupyter Notebook Flower_recog_Model_1.ipynb

Run the cells sequentially to:

Install dependencies

Load and preprocess the dataset

Build and train the CNN model

Evaluate model performance

Make predictions on new images

Model Architecture
The CNN model includes:

Convolutional layers

Max pooling layers

Dropout layers for regularization

Dense layers for classification

Results
The notebook includes visualizations of:

Training and validation accuracy

Training and validation loss

Sample predictions

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements.

License
This project is licensed under the MIT License - see the LICENSE file for details.
