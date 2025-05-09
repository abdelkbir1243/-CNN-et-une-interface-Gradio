# 🖼️ CIFAR-10 Image Classification with CNN and Gradio

[![Open in Colab]([https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/cifar10-cnn-gradio/blob/main/notebooks/CIFAR10_Classification.ipynb](https://colab.research.google.com/drive/1LZsCh4P3ME7HgWvs1gkReoTKqlgvEk1a#scrollTo=LsZ7nhMgv9X1))
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow Version](https://img.shields.io/badge/TensorFlow-2.8%2B-orange)
![Gradio Version](https://img.shields.io/badge/Gradio-3.0%2B-green)

A complete implementation of a Convolutional Neural Network (CNN) for CIFAR-10 image classification, with an interactive web interface using Gradio.

![Demo Interface](media/demo_screenshot.png)

## 📋 Table of Contents
- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Results](#-results)
- [Video Tutorial](#-video-tutorial)
- [License](#-license)

## ✨ Features
- CNN model with **71.4% test accuracy**
- Interactive Gradio web interface
- Easy deployment on Google Colab with GPU support
- Complete documentation and video walkthrough
- Pre-trained model available

## 🛠 Installation

### Prerequisites
- Python 3.8+
- pip package manager

### Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/cifar10-cnn-gradio.git
cd cifar10-cnn-gradio

# Install dependencies
pip install -r requirements.txt
.
├── models/               # Model definitions and weights
│   ├── train.py          # Training script
│   └── cifar10_cnn.h5    # Pretrained model
├── notebooks/            # Jupyter notebooks
│   └── CIFAR10_Classification.ipynb  # Main notebook
├── app.py                # Gradio application
├── requirements.txt      # Dependencies
├── README.md             # This file
└── media/                # Demo assets
    ├── demo.mp4          # Video tutorial
    └── demo_screenshot.png
