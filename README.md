# Handwritten Recognition Model
This project implements a handwritten recognition model using Convolutional Neural Networks (CNNs) with TensorFlow. The model is trained to recognize handwritten characters from images.

# Overview
The handwritten recognition model is built using TensorFlow, a popular deep learning framework. It utilizes a CNN architecture for feature extraction and classification. The model is trained on a dataset consisting of handwritten character images and their corresponding labels.

# Dataset
The dataset used in this project is the English Handwritten Characters Dataset available on Kaggle "https://www.kaggle.com/datasets/dhruvildave/english-handwritten-characters-dataset". This dataset contains images of handwritten characters in English alphabets (both uppercase and lowercase), numbers (0-9), and some special characters. It consists of approximately 372,451 images with corresponding labels.

Dataset Details:
- Format: Images in JPG format with dimensions varying across samples.
- Labels: Each image is associated with a label indicating the character it represents.
- Character Classes: The dataset covers English alphabets (A-Z, a-z), digits (0-9), and special characters.
  
This dataset provides a diverse set of handwritten characters, enabling the model to learn and recognize a wide range of writing styles and variations.

# Usage
1. Prepare your handwritten images by placing them in the Img directory.
2. Create a CSV file (english.csv) containing the labels for each image.
3. Run the following command to train the model:
python train_model.py
4. After training, you can evaluate the model using:
python evaluate_model.py

# Model Evaluation
The model is evaluated using various metrics such as accuracy, precision, recall, and F1 score. Additionally, a confusion matrix is generated to visualize the model's performance.
