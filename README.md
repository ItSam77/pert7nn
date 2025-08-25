# Convolutional Neural Networks for Flower Classification

## Dataset
The dataset is sourced from Roboflow: https://universe.roboflow.com/jacob-solawetz/flowers_classification/dataset/6

This dataset contains flower images with 2 classes: **daisy** and **dandelion**. The dataset is already split into train, test, and validation sets on Roboflow.

## How to Run the Notebook

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ItSam77/pert7nn.git
   cd PERT7-2
   ```

2. **Install requirements:**
   
   For Google Colab:
   ```python
   !pip install -r requirements.txt
   ```
   
   For Jupyter Notebook:
   ```python
   %pip install -r requirements.txt
   ```

3. **Run the notebook:**
   Create a new code block with the installation command above and execute it, then you can run the main notebook.

## Features

The notebook includes the following features:
- Data augmentation
- Pre-trained model implementation
- Hyperparameter tuning using Keras Tuner
- Model selection using Keras Tuner
- Early stopping callbacks
