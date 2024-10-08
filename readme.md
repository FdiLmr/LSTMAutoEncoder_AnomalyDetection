# LSTM AutoEncoder CNN for Heartbeat Anomaly Detection

This repository contains the implementation of a deep learning model that combines LSTM (Long Short-Term Memory) AutoEncoders and CNN (Convolutional Neural Networks) to detect anomalies in heartbeat signals. The model is designed to process time-series data from electrocardiograms (ECGs) to identify irregular heartbeat patterns.

## Project Overview

Cardiac arrhythmias are irregular heartbeats that can indicate potential health risks. Detecting these anomalies from ECG data is crucial in preventive healthcare. In this project, an LSTM AutoEncoder is used to model the normal heartbeat patterns, and a Convolutional Neural Network (CNN) is applied to further enhance the feature extraction process. Anomalies are identified by comparing reconstruction errors of the ECG signals.

### Key Features

- **LSTM AutoEncoder**: Captures temporal dependencies in ECG signals and learns to reconstruct normal heartbeat patterns.
- **CNN**: Extracts spatial features from the ECG data to improve anomaly detection.
- **Anomaly Detection**: Uses reconstruction error from the autoencoder to identify irregular heartbeats.

## Table of Contents

1. [Installation](#installation)
2. [Data](#data)
3. [Model Architecture](#model-architecture)
4. [Training](#training)
5. [Results](#results)
6. [Usage](#usage)
7. [Contributing](#contributing)
8. [License](#license)

## Installation

To run this project, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/yourusername/LSTMAutoEncoderCNNforHeartBeatAnomalyDetection.git
cd LSTMAutoEncoderCNNforHeartBeatAnomalyDetection
pip install -r requirements.txt

## Data

The dataset used in this project is the [MIT-BIH Arrhythmia Database](https://physionet.org/content/mitdb/1.0.0/). It contains time-series data of ECG signals, each with a label indicating the presence of an anomaly.

## Model Architecture

The model architecture consists of an LSTM AutoEncoder followed by a CNN. The LSTM AutoEncoder learns the normal heartbeat patterns, while the CNN enhances feature extraction.

## Training

The model is trained using the training dataset. The training process involves the following steps:

1. Data preprocessing
2. Model initialization
3. Model training
4. Model evaluation 


 
