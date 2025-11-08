# Brain Tumor Classification with PyTorch (CNN)

This project implements a Convolutional Neural Network (CNN) in PyTorch to classify brain tumor types from MRI scans. It follows the workflow demonstrated in the YouTube tutorial and covers data preparation, model creation, training, evaluation, and prediction visualization.

---

## 🧠 Project Overview

The goal of this project is to build and train a CNN capable of classifying MRI brain images into **four tumor categories**. The model uses PyTorch’s deep learning framework, trained on a Kaggle brain tumor MRI dataset, and achieves strong accuracy on unseen test data.

---

## 📂 Features

- End-to-end PyTorch workflow  
- Image preprocessing using `torchvision.transforms`  
- Custom CNN architecture with Convolution, ReLU, MaxPooling, Flatten, and Linear layers  
- Training loop with forward/backward pass + parameter optimization  
- Model evaluation with accuracy calculation  
- Visualization of predictions on random images  
- Achieves **~96% test accuracy** in the tutorial

---

## 🛠️ Technologies Used

- **Python**
- **PyTorch**
- **Torchvision**
- **Matplotlib**
- **Jupyter Lab / Notebook**

---

## 📦 Requirements

You will need:

- Python 3.x  
- PyTorch + Torchvision  
- Matplotlib  
- Jupyter Lab / Notebook  

Install everything with:

```bash
pip install torch torchvision matplotlib jupyterlab
```
---

## 🤝 Acknowledgments

This project is based on the concepts taught in the YouTube tutorial.
All dataset credit belongs to the original Kaggle contributors.
