# 🧠 Deep Learning Project  
## Handwritten Digit Recognition using CNN (MNIST) - PyTorch

---

# 📌 Problem Description
This project implements a Deep Learning model using a Convolutional Neural Network (CNN) to recognize handwritten digits from the MNIST dataset.  
The goal is to correctly classify digits (0–9) from grayscale images.

---

# 📊 Dataset
The dataset used is the **MNIST dataset**, which is a standard benchmark dataset for handwritten digit recognition.

- Dataset is automatically loaded using PyTorch torchvision library
- It contains 60,000 training images and 10,000 testing images
- Each image is 28x28 grayscale

### Dataset Link:
http://yann.lecun.com/exdb/mnist/

or PyTorch Built-in Dataset:
https://pytorch.org/vision/stable/datasets.html

---

# ⚙️ Model Architecture
A Convolutional Neural Network (CNN) is used with the following structure:

- Convolution Layer (32 filters)
- Batch Normalization
- ReLU Activation
- MaxPooling
- Convolution Layer (64 filters)
- Batch Normalization
- ReLU Activation
- MaxPooling
- Dropout
- Fully Connected Layer (128 neurons)
- Output Layer (10 classes)

---

# 🚀 Enhancements Used
- Batch Normalization
- Dropout Regularization

---

# 🏋️ Training Details
The model was trained using:
- Optimizers: Adam and SGD
- Loss Function: CrossEntropyLoss
- Metrics: Accuracy and Loss
- Train/Validation Split: 80/20

---

# 📈 Experiments
Two experiments were conducted:

| Model | Optimizer | Accuracy | Loss |
|------|----------|----------|------|
| CNN Model 1 | Adam | XX% | XX |
| CNN Model 2 | SGD | XX% | XX |

---

# 📊 Results Visualization
The following graphs were generated:
- Training vs Validation Loss
- Training vs Validation Accuracy

---

# 🧪 Evaluation
The model was evaluated on the test dataset using:
- Accuracy
- Loss

Final performance is printed after training.

---

# 🛠️ How to Run the Project

## 1. Install Requirements
```bash
pip install torch torchvision matplotlib pandas numpy