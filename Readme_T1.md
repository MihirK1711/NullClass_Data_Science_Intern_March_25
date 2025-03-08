# Task 1: Visualizing Activation Maps (Grad-CAM)

## Overview
This project visualizes activation maps using Grad-CAM to understand which image regions activate CNN filters in an emotion detection model trained on the FER2013 dataset.

## Dataset
- **FER2013**: A facial emotion recognition dataset containing grayscale 48x48 images.
- Download from [Kaggle](https://www.kaggle.com/datasets/msambare/fer2013)

## Model
- Uses a pre-trained **VGG16** model.
- Extracts activation maps from the `block5_conv3` layer.
- Grad-CAM is used to generate heatmaps highlighting important image regions.

## Installation
Ensure you have Python installed, then install dependencies:
pip install -r requirements.txt

## Running the Notebook
1. Open the Jupyter Notebook (`Visualize_Activation_Maps_Notebook.ipynb`).
2. Run the cells to visualize activation maps.

## Running as a Python Script
python visualize_activation_maps.py

## Output
- Displays the original image alongside the Grad-CAM heatmap overlay.
- Helps analyze which facial regions influence emotion classification.

## Submission Structure
```
Task1_Activation_Maps/
│── visualize_activation_maps.py
│── Visualize_Activation_Maps_Notebook.ipynb
│── requirements.txt
│── README.md
```

