# Fashion-MNIST Exploration with Deep Belief Networks (DBN)

## Overview
This project implements a **Deep Belief Network (DBN)** for classifying images from the **Fashion-MNIST** dataset. A DBN is a stack of **Restricted Boltzmann Machines (RBMs)** trained in a greedy layer-wise manner, capturing hierarchical feature representations. The project also compares DBN performance against Feedforward Neural Networks (FNN) and Convolutional Neural Networks (CNN) under noisy and adversarial conditions.

## Features
- **DBN Implementation**: Built using multiple layers of RBMs
- **RBM Training**: Contrastive Divergence for unsupervised learning
- **Dataset**: Fashion-MNIST (60,000 training, 10,000 test samples, 10 classes)
- **Visualization**:  
  - Receptive fields of hidden layers  
  - Clustering of learned representations  
  - Robustness analysis against noise and adversarial attacks  
- **Model Comparison**: DBN vs. FNN vs. CNN in classification robustness
- **Adversarial Defense**: Investigating top-down reconstruction to counter adversarial attacks

## Project Structure
```plaintext
.
├── DBN.py                 # Deep Belief Network implementation
├── RBM.py                 # Restricted Boltzmann Machine implementation
├── dbn_project.ipynb      # Main Jupyter Notebook with experiments
├── README.md              # Project documentation
```


