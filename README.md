# SNN-sEMG-GestureClassification-ForceTracking

This repository contains the implementation of a Spiking Neural Network (SNN) for both hand gesture classification and continuous force tracking using surface electromyographic (sEMG) signals. The model is optimized for real-time processing on low-power FPGA devices.

## Description
This notebook focuses on the recognition of gestures based on surface electromyographic (sEMG) signals and force data using Spiking Neural Networks (SNNs). The objective is to develop a model that can classify human gestures based on sEMG signals and force measurements. Accurate modeling of hand movement based on sEMG signals offers exciting opportunities for developing complex prosthetic devices and human-machine interfaces, advancing from discrete gesture recognition towards continuous movement tracking. This project evaluates the performance of SNNs in discrete finger gesture recognition, using the NinaPro DB5 dataset, and in continuous finger force modeling using the Hyser dataset.

## Notebook Content

### 1. Dependencies and Functions
- Importing necessary libraries.

### 2. Function Definitions
- Defining utility functions for data preprocessing, dataset creation, and SNN model construction.

### 3. Data Loading and Preprocessing
- Loading sEMG and force data.
- Applying preprocessing techniques to prepare the data for model training.

### 4. Model Creation
- Implementing a Spiking Neural Network using the snntorch library.
- Configuring the model architecture and loss functions.

### 5. Model Training
- Procedure for training the SNN model on preprocessed data.
- Visualization of training metrics to monitor model performance.

### 6. Evaluation and Results
- Evaluating the model's performance on test data.
- Discussing the obtained results and potential applications.

## Usage Instructions
1. Clone the repository and open the notebook in a Jupyter environment or Google Colab.
2. Install the necessary dependencies by executing the corresponding cells.
3. Follow the notebook sections to preprocess the data, create and train the model, and evaluate its performance.

## License
This project is released under the MIT license.
