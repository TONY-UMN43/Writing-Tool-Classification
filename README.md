# Writing Tool Classification (PyTorch)

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

| Variation     | Description                             | Accuracy | Folder |
|---------------|-----------------------------------------|----------|--------|
| ⚪️ Single-label (Binary) | Classify between pen and pencil                 | 91%      | [`/single-label`](./single-label) |
| 🔵 Multi-class          | Classify between pen, pencil, marker, and crayon  | 89%      | [`/multi-class`](./multi-class)  |
| 🔴 Multi-label          | Classify pen, pencil or both (e.g. pen + pencil) | 88%      | [`/multi-label`](./multi-label)  |

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
