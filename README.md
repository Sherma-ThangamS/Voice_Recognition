# Voice Recognition Project

## Introduction

This repository contains the code and documentation for a Voice Recognition project, which is a part of the CodersCave Data Science Internship - Phase 2, Task 1. The project focuses on building a voice recognition system using machine learning techniques.

## Dataset

The dataset used in this project was obtained from Kaggle. It consists of a collection of audio recordings categorized into different classes. The data source can be found here: [Kaggle Dataset](link_to_dataset)

## Project Overview

The project can be summarized as follows:

1. **Data Collection**: A diverse set of audio data was collected from the Kaggle dataset.

2. **Data Preprocessing**: The audio data underwent extensive preprocessing, which included audio loading, feature extraction using Mel-Frequency Cepstral Coefficients (MFCCs), and data standardization.

3. **Model Development**: A Convolutional Neural Network (CNN) model was developed for voice recognition. The model architecture included techniques such as Batch Normalization, Dropout, and Regularization to enhance its performance.

4. **Overfitting Mitigation**: Special attention was given to addressing overfitting. Strategies like Batch Normalization and Dropout were implemented to ensure the model's robustness.

5. **Training Optimization**: Early stopping was applied during model training to improve training efficiency and prevent overfitting.


## Results

The model achieved an accuracy of 97.7 on the test dataset, accuracy of 72 on the validation dataset, showcasing its effectiveness in voice recognition tasks. The project successfully reduced overfitting, resulting in a robust system.

## Acknowledgments

- Kaggle for providing the dataset used in this project.
- CodersCave for the opportunity to work on this project during the Data Science Internship.

## License

This project is licensed under the [MIT License](LICENSE), which means you are free to use, modify, and distribute the code as long as you provide appropriate attribution and retain the same license for derivative works.
