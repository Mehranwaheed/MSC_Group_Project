# Anomaly Detection in Products

This repository contains code for an anomaly detection project using machine learning techniques. The project aims to identify anomalies in product images using a combination of data preprocessing, feature extraction, and classification.

# Files:
under_sample_py.py: This script performs undersampling of the dataset to address class imbalance issues. It balances the number of normal and anomaly images in the dataset.

feature_extraction.py: This script extracts features from the preprocessed images using various techniques, including ResNet50 and VGG16 pre-trained models.

Augment_sample_py.py: This script performs data augmentation by rotating circular regions within the images to generate additional training samples.

prototype.pkl: This file contains a saved machine learning model trained on the preprocessed and augmented dataset.

prototype.py: This script demonstrates how to load the saved model and use it to predict anomalies in new images. It serves as a prototype for deploying the anomaly detection system.

# Usage:
Run under_sample_py.py to balance the dataset by undersampling the majority class (normal images).

Execute feature_extraction.py to extract features from the preprocessed images using different methods.

Use Augment_sample_py.py to perform data augmentation by rotating circular regions within the images.

Load the saved model from prototype.pkl using prototype.py and use it to predict anomalies in new images.
