# Speech Emotion Recognition using Convolutional Neural Networks

## Overview
This project focuses on recognizing speech emotions using a Convolutional Neural Network (CNN). The dataset consists of audio recordings categorized into different emotional classes. The audio files are preprocessed using librosa, and Mel-frequency cepstral coefficients (MFCCs) are extracted as features for model training.

## Data Processing
- Audio files are loaded, and MFCCs are computed for feature extraction.
- Labels are encoded using sklearn's LabelEncoder.
- The dataset is split into training and testing sets.

## Model Architecture
- A CNN is implemented using Keras with Conv2D, MaxPooling2D, Flatten, Dense, Dropout, and BatchNormalization layers.
- Adamax optimizer is used with sparse categorical crossentropy loss for model compilation.
- Early stopping is employed to prevent overfitting during training.

## Model Training
- The model is trained for 30 epochs with a batch size of 32.
- Training progress is monitored using validation data.

## Model Evaluation
- The model achieves high accuracy on the close dataset, reaching approximately 97.78%.
- Performance on the open dataset is slightly lower, with an accuracy of 72.06%.
