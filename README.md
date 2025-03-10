# Esophageal Cancer Classifier using ResNet50 Model

This repository contains code and resources for classifying esophageal cancer stages (Normal, Early Cancer, Advanced Cancer) using the Kvasir V2 dataset and a ResNet50 model implemented in PyTorch with CUDA support.

## Dataset
The Kvasir V2 reorganized dataset is included in this repository using Git Large File Storage (LFS) due to its size (~4 GB). Alternatively, if LFS is not accessible, an external download link is provided.

### Where to Get the Dataset
- **Source**: The original Kvasir V2 dataset is provided by the Simula Research Laboratory and the University of Oslo.
- **Official Link**: [Kvasir V2 Dataset](https://datasets.simula.no/kvasir/)
  - You may need to request access or follow the dataset’s terms of use. The dataset contains ~8,000 endoscopic images across various gastrointestinal conditions, which we have reorganized for esophageal cancer classification.
- **This Repository**: The reorganized dataset (`kvasir_v2_reorganized`) with train and validation splits is available via Git LFS in this repo. Download instructions are below.

### How to Use the Dataset
1. **Clone the Repository**:
   - Clone this repository to your local machine:
     ```bash
     git clone https://github.com/sagargour24/Esophageal-Cancer-Classifier-using-Resnet50-Model.git
     cd Esophageal-Cancer-Classifier-using-Resnet50-Model
