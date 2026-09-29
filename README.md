# Autoencoder-VAE-Image-Reconstruction
Autoencoder and Variational Autoencoder for Image Reconstruction

## Practical No. 03

This project implements an Autoencoder and a Variational Autoencoder (VAE) for image reconstruction and image generation using the MNIST dataset.

## Objectives

- Implement an Autoencoder
- Implement a Variational Autoencoder
- Reconstruct MNIST images
- Generate new images using VAE
- Compare Autoencoder and VAE performance

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- MNIST Dataset
- Google Colab / Jupyter Notebook

## Models

### Autoencoder

The Autoencoder consists of:

Input Image → Encoder → Latent Representation → Decoder → Reconstructed Image

### Variational Autoencoder

The VAE consists of:

Input Image → Encoder → Mean & Variance → Sampling → Decoder → Reconstructed Image

## Results

The models are evaluated using reconstruction loss and Mean Squared Error (MSE).

The VAE is additionally used to generate new images by sampling from its latent space.

## How to Run

Install the required libraries:

```bash
pip install tensorflow numpy matplotlib
