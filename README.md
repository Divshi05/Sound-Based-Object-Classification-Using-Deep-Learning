# Sound-Based-Object-Classification-Using-Deep-Learning

This project implements a deep learning model to classify urban sound clips into 10 distinct categories using the UrbanSound8K dataset.

Features
Data Processing: Extracts Mel-Frequency Cepstral Coefficients (MFCCs) for robust audio feature representation.

Model Architecture: Dense Neural Network with multiple layers and dropout for regularization.

Training: Uses categorical cross-entropy loss, Adam optimizer, and early stopping with model checkpointing.

Performance: Achieves ~90% accuracy in classifying urban sound events.

Usage
Clone the repo and download the UrbanSound8K dataset.

Run the feature extraction script to generate MFCC features.

Train the model with the provided training script.

Evaluate performance on the test set.

Dependencies
Python 3.x

TensorFlow/Keras

Librosa

Pandas

NumPy

Matplotlib
