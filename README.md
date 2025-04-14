# 🖥️ Handwritten Digits Classification with TensorFlow

**Author:** Jullian Alcantara  
**Tools Used:** Python, TensorFlow, Keras, Matplotlib, NumPy  

---

## 📌 Project Overview

This project applies a Convolutional Neural Network (CNN) to classify images of handwritten digits (0–9) from the **MNIST dataset** using TensorFlow. The goal was to build a high-performing image classification model and visualize its predictions.

---

## 🎯 Objective

- Build and train a deep learning model to classify handwritten digits  
- Optimize model performance through network architecture design  
- Visualize classification results and model accuracy  

---

## 📈 Dataset

- **MNIST dataset**: 70,000 grayscale images of handwritten digits (28×28 pixels)
- **Source**: Included in TensorFlow Datasets  

---

## ⚙️ Methodology

1. **Data Loading & Preprocessing**
   - Normalized pixel values to a [0,1] range
   - Reshaped images for CNN input

2. **Model Architecture**
   - Convolutional Neural Network (CNN)
   - Layers: Conv2D → MaxPooling → Flatten → Dense → Dropout → Output

3. **Model Training**
   - Optimizer: Adam
   - Loss Function: Sparse Categorical Crossentropy
   - Accuracy tracked over training and validation sets

4. **Model Evaluation**
   - Assessed accuracy on the test dataset
   - Visualized sample predictions with true vs. predicted labels

---

## 📊 Key Results

- Achieved **over 99% accuracy** on the training set and high performance on unseen test data.
- Demonstrated the practical application of CNNs for image classification problems.
- Visualized model predictions on sample test images.

---

## 📂 How to Run

```bash
# Install dependencies
pip install tensorflow matplotlib numpy

# Run the notebook
Open 'classification_handwritten_digits_tensorflow.ipynb' in Jupyter or VS Code
