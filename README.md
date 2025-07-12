# Rice Type Classification

A deep learning–based image classification project to distinguish among different types of rice grains using the Rice Type Classification dataset from Kaggle.

---

## Table of Contents

- [Project Overview](#project-overview)  
- [Dataset](#dataset)  
- [Environment & Dependencies](#environment--dependencies)  
- [Usage](#usage)  
- [Notebook Structure](#notebook-structure)  
- [Results](#results)  
- [Contributing](#contributing)  
- [License](#license)  
- [Acknowledgments](#acknowledgments)  

---

## Project Overview

This project leverages convolutional neural networks (CNNs) implemented in PyTorch to classify images of rice grains into their respective types. You’ll find data loading, exploratory analysis, model definition, training/evaluation loops, and visualizations of performance metrics.

---

## Dataset

**Rice Type Classification**  
– Source: Kaggle  
– Link: https://www.kaggle.com/datasets/mssmartypants/rice-type-classification  

The dataset contains a CSV file (`riceClassification.csv`) with image file paths and labels for each rice variety. Images are organized under subdirectories of the Kaggle input.

---

## Environment & Dependencies

- **Python** 3.7+  
- **Key libraries**  
  - numpy  
  - pandas  
  - matplotlib  
  - PyTorch  
  - torchsummary  
  - scikit-learn  

You can install everything via:

```bash
pip install numpy pandas matplotlib torch torchvision torchsummary scikit-learn
