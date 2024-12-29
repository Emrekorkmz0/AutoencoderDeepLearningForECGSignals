

# ECG Feature Extraction with Autoencoder

This project demonstrates the use of an autoencoder for feature extraction from an Electrocardiogram (ECG) dataset. The extracted features can be utilized for various downstream tasks such as classification, anomaly detection, or visualization.

Table of Contents

Introduction

Dataset

Methodology

Project Structure

Installation

Usage

Results

Future Work


# Introduction

Electrocardiograms (EKGs) are widely used for monitoring cardiac activity. However, raw EKG data is often high-dimensional and noisy, making feature extraction a critical preprocessing step. This project employs an autoencoder, a type of neural network, to extract meaningful features from EKG data. These features are lower-dimensional representations that capture the essential information in the signal.

# Dataset

The dataset used in this project consists of ECG signals. Each signal has been preprocessed to remove noise and artifacts. Details of the dataset preprocessing steps are provided in the code. 
number of total dataset is 30.988 and there are 6 class



# Autoencoder Architecture:

The autoencoder consists of an encoder and a decoder.

The encoder compresses the input ECG signal into a latent representation.

The decoder reconstructs the signal from the latent representation.

# Training:

The model is trained using binary_crossentropy as the reconstruction loss.

# Feature Extraction:

Once trained, the encoder part of the autoencoder is used to extract features from the ECG signals.

# Results

The autoencoder achieves low reconstruction error, indicating effective feature learning.

Extracted features are shown to capture key characteristics of the EKG signals.

Visualizations of the reconstructed signals and latent space are provided in the results folder.
