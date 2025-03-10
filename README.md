# Kvasir V2 Dataset - Esophageal Cancer Classification

This repository contains a Jupyter notebook and supporting files for training a ResNet50 deep learning model to classify endoscopic images from the Kvasir V2 dataset into stages of esophageal cancer (Normal, Early Cancer, Advanced Cancer). The notebook leverages PyTorch and CUDA for GPU acceleration and includes data preprocessing, model training, and evaluation.

## Overview
- **Dataset**: Kvasir V2 (a publicly available endoscopic dataset with ~8,000 images across various gastrointestinal conditions).
- **Task**: Binary and multi-class classification of esophageal cancer stages.
- **Model**: ResNet50 (pretrained on ImageNet) fine-tuned for esophageal cancer detection.
- **Environment**: Python 3.11 with PyTorch, CUDA 12.8, and additional libraries.
- **Hardware**: NVIDIA RTX A4000 Laptop GPU (or compatible GPU).

## Repository Contents
- `train_esophageal_classifier.ipynb`: Jupyter notebook with the complete training pipeline.
- `kvasir_v2_reorganized/`: Directory containing the reorganized Kvasir V2 dataset (train and validation splits).
- `esophageal_classifier_kvasir_v2_cnn.pth`: Pretrained model weights (optional, if included).
- `README.md`: This file with usage instructions.
- `requirements.txt`: List of Python dependencies (to be created).

## Instructions to Use the Jupyter Notebook

### 1. **Clone the Repository**
Clone this repository to your local machine:
```bash
git clone https://github.com/yourusername/kvasir-esophageal-cancer-dataset.git
cd kvasir-esophageal-cancer-dataset
