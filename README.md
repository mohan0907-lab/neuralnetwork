# 🌸 Flower Recognition Using CNN 🌼

[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)](https://www.tensorflow.org/)
[![Python](https://img.shields.io/badge/Python-3.x-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

A convolutional neural network (CNN) model for classifying flowers into 5 categories: daisy, dandelion, rose, sunflower, and tulip.


## ✨ Features

- 🖼️ Image preprocessing with TensorFlow's `ImageDataGenerator`
- 🧠 CNN architecture with dropout regularization
- 📊 Training visualization (accuracy/loss curves)
- 🔍 Prediction on custom flower images
- 📈 Model evaluation metrics

## 🛠️ Requirements

- Python 3.x
- Jupyter Notebook
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- OpenCV

## 🚀 Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/bhuvansai93/neuralnetwork.git
   cd neuralnetwork

2. Install dependencies
  (We recommend using a virtual environment)
   ```bash
    pip install -r requirements.txt
3. Run the notebook
    ```bash
    jupyter notebook code_ml_tutorial_23098103.ipynb


📁 Dataset
The model uses 4,317 flower images across 5 categories:

Flower	Count	Example
Daisy	764	🌼
Dandelion	1,052	🌞
Rose	784	🌹
Sunflower	733	🌻
Tulip	984	🌷


🧮 Model Architecture

Model: "sequential"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
conv2d (Conv2D)              (None, 148, 148, 32)      896       
_________________________________________________________________
max_pooling2d (MaxPooling2D) (None, 74, 74, 32)        0         
_________________________________________________________________
conv2d_1 (Conv2D)            (None, 72, 72, 64)        18496     
_________________________________________________________________
max_pooling2d_1 (MaxPooling2 (None, 36, 36, 64)        0         
_________________________________________________________________
dropout (Dropout)            (None, 36, 36, 64)        0         
_________________________________________________________________
flatten (Flatten)            (None, 82944)             0         
_________________________________________________________________
dense (Dense)                (None, 128)               10616960  
_________________________________________________________________
dense_1 (Dense)              (None, 5)                 645       
=================================================================
Total params: 10,636,997
Trainable params: 10,636,997
Non-trainable params: 0



📊 Results
Training Results

Evaluation Metrics:

Training Accuracy: 98.7%

Validation Accuracy: 92.3%

Test Accuracy: 90.8%



🏃‍♂️ Usage
1. Open the Jupyter Notebook:
```bash
jupyter notebook Flower_recog_Model_1.ipynb


Run cells sequentially to:

Load and preprocess data

Build and train the model

Evaluate performance

Make predictions



📜 License
Distributed under the MIT License. See LICENSE for more information.
