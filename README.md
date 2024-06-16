## Playing Card Classification Project

# Overview

Welcome to the Playing Card Classification project! This project focuses on developing an artificial intelligence model capable of accurately recognizing and classifying images of playing cards. By leveraging both traditional machine learning techniques and deep learning methodologies, we aim to achieve robust performance in classifying a diverse set of playing card images.

# Dataset
[You can access dataset from this Kaggle link: ](https://www.kaggle.com/datasets/gpiosenka/cards-image-datasetclassification)

The dataset used in this project consists of images representing 53 different classes of playing cards. Each class corresponds to a unique card type and suit combination (e.g., 'ace of clubs', 'king of hearts'). The dataset is split into three subsets:

Training Set: Contains 7624 images
Test Set: Contains 265 images
Validation Set: Contains 265 images

# Methodology
Traditional Machine Learning Methods
K-Nearest Neighbors (KNN): Utilizes neighborhood relations to classify each example in the dataset.
Gaussian Naive Bayes (GNB): Assumes features are normally distributed within each class.
Deep Learning Method
Convolutional Neural Network (CNN): Employs convolutional layers for automatic feature extraction from images, followed by dense layers for classification.
Installation
To run this project, ensure you have Python installed along with the necessary libraries:

'''
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras
'''

You'll also need the Kaggle API to download the dataset. Make sure your kaggle.json file is correctly set up.

# Getting Started

# Clone the Repository:

'''
git clone https://github.com/yourusername/playing-card-classification.git
cd playing-card-classification
'''

# Download and Extract the Dataset:

'''
!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle/
!kaggle datasets download -d gpiosenka/cards-image-datasetclassification
!unzip cards-image-datasetclassification.zip -d data/
'''

# Explore the Notebooks:
Navigate to the notebooks directory and use the Jupyter notebooks to explore the dataset and experiment with models.

# Train and Evaluate Models:
Use scripts in the src directory to train and evaluate different models.
