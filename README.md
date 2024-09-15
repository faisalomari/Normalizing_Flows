# Normalizing Flows - Advanced Course on Deep Generative Models

## Overview
This repository contains the solution for **Exercise 6: Normalizing Flows** from the Advanced Course on Deep Generative Models, Spring 2024. The assignment focuses on implementing a normalizing flow (NF) model and training it on the MNIST dataset. The notebook includes log-likelihood computation, sample generation, and latent traversals.

## Assignment Details

- **Instructor**: Dan Rosenbaum
- **Due Date**: 14 July 2024
- **Main File**: `main.ipynb`

### Key Tasks
1. **Implement Normalizing Flow Model**: 
   - The model consists of 4 NF layers with an MLP using 5 linear layers and ReLU activations.
   - Implement a forward function that maps data points \(x\) to their latent representation \(z\).
   - Implement an inverse function to generate samples from the latent space \(z\).
   - Train the model using a Standard Gaussian prior, and log the likelihood for both training and validation data.

2. **Sample Generation**: 
   - Generate and visualize samples from the trained model. 
   - Report the log-likelihood for the test set and plot the training/validation curves.

3. **Layerwise Transformation**: 
   - Show how latent vectors \(z\) gradually transform into data samples \(x\) across the NF layers. Visualize this transformation by showing intermediate steps from the latent space to the data space.

4. **Latent Traversals**: 
   - Perform latent traversals by linearly interpolating between two different latent representations of digits. Visualize how one digit morphs into another.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/normalizing-flows-assignment.git
   cd normalizing-flows-assignment
2.Open the main.ipynb notebook in Google Colab or Jupyter Notebook.

3. Run all cells to:
    * Train the Normalizing Flow model on the MNIST dataset.
    * Generate and visualize samples.
    * Perform latent traversals and show transformation grids.
