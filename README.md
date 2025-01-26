# CelebFaces Training Using GANs

This project leverages Generative Adversarial Networks (GANs) to generate and analyze realistic human face images using the CelebA dataset. The project demonstrates the power of GANs for image synthesis and explores techniques to improve training stability and output quality.

## Project Overview

- **Objective**: Train a GAN model to generate realistic human face images from the CelebFaces dataset.
- **Dataset**: [CelebA Dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) containing over 200,000 celebrity images with diverse attributes.
- **Techniques**:
  - Preprocessing images for model training.
  - Implementing GAN architecture with a Generator and Discriminator.
  - Fine-tuning hyperparameters for optimal results.

## Files Included

- `CelebFaces_Training_using_GANs.ipynb`: Main Jupyter Notebook containing all code and results.
- `data/`: Folder containing sample images from the CelebA dataset (not included here for size constraints).
- `output/`: Generated face images from the trained GAN.

## Key Features

1. **Data Preprocessing**:
   - Resizing and normalizing images.
   - Splitting the dataset into training and testing sets.

2. **GAN Architecture**:
   - Implementation of a custom Generator and Discriminator.
   - Loss functions to balance adversarial training.

3. **Training and Evaluation**:
   - Visualization of training progress.
   - Evaluation metrics for GAN performance.

4. **Results**:
   - Showcase of generated faces.
   - Analysis of model performance and limitations.

## Requirements

- Python 3.10+
- Jupyter Notebook using Google colab for predownloaded Libraries
- Libraries:
  - PyTorch
  - NumPy
  - Matplotlib

Install the required packages using:
```bash
pip install -r requirements.txt
