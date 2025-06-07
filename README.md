# Writing Tool Classification (PyTorch)

## License
This project is for **viewing purposes only**.  
Do not copy, modify, or redistribute any part of this code without explicit permission.  
© 2025 Tony Akinyemi. All rights reserved.

A Deep Learning Project that explores **single-label**, **multi-class**, and **multi-label** using PyTorch. The goal was to use my own dataset of Pens and Pencils to train a Convolutional Neural Network Model that can make accurate predictions about any image that contains a pencil, pen, or both. 

# Project Highlights
- Created and Trained CNN Models using **PyTorch**
- Developed pipelines for **binary**,**multi-class** and **multi-label** classification
- Visualized results with **matplotlib** and **confusion matrices**
- Documented results in **Google Collabs**
- 
# This project scans an image of a pen or pencil and determines which writing utensil is in the image. 

# Technology Used
- GoogleCollabs
- Python, PyTorch, PyTorchVision, PyTorchUtils,
- SkLearnMetrics
- MatPlotLib for Visualization

# Variations of Model

| Variation     | Description                             | Training Accuracy | Testing Accuracy | Folder | DataSet |
|---------------|-----------------------------------------|----------|--------|--------|--------|
| ⚪️ Binary-Class  | Classify between pen and wooden pencil                 | 94% | 85%    | [`/Binary-Class`](./Binary-Class) |[`Binary-Class-DataSet`](https://drive.google.com/drive/folders/1Ge-QIjMrwEb83_CdX60tHpdv6QvaOkPr?usp=sharing) |
| 🔵 Multi-Class          | Classify between pen, wooden pencil, marker, and crayon  | 89% | 74%     | [`/Multi-Class`](./Multi-Class)  |[`Multi-Class`](./Multi-Class)  |
| 🔴 Multi-Label          | Classify pen, wooden pencil or both (e.g. pen + wooden pencil) | 88% | 71%    | [`/Multi-Label`](./Multi-Label)  || [`Multi-Label`](./Multi-Label)  |


---

# Model Architecture (Binary)
- 3 Layer CNN
- ReLU Activation Functions
- MaxPooling & Dropout
- Cross-Entropy Loss Function
- Adam Optimizer

# Visualization
- Training vs Validation Plots
- Confusion Matrix
- Predictions with Labels


# What I Learned
- How to create my own DataSets using both ImageFolders and CSV Files
- How to use CNN architectures to classify images
- When to use CrossEntropyLoss and when to use BinaryCrossEntropyLoss
- How to address Overfitting by using Dropout() layers and BatchNormalization.
