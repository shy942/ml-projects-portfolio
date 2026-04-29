# 🧠 Handwritten Digit Classification using CNN (MNIST)

## 📌 Project Overview

This project implements a Convolutional Neural Network (CNN) to classify handwritten digits (0–9) using the MNIST dataset. The model is built using TensorFlow/Keras and demonstrates a complete deep learning workflow, including data preprocessing, model training, evaluation, and visualization.

---

## 🎯 Objectives

* Build a deep learning model for image classification
* Understand CNN architecture for computer vision tasks
* Evaluate model performance using accuracy and loss metrics
* Visualize training and validation performance

---

## 📂 Dataset

The MNIST dataset contains:

* 70,000 grayscale images of handwritten digits
* Image size: 28 × 28 pixels
* 10 classes (digits 0–9)

The dataset is automatically loaded using Keras:

```python
from tensorflow.keras.datasets import mnist
```

---

## ⚙️ Technologies Used

* Python
* TensorFlow / Keras
* Matplotlib
* scikit-learn

---

## 🧹 Data Preprocessing

* Normalized pixel values to range [0, 1]
* Reshaped images to (28, 28, 1) for CNN input
* Split into training and testing sets

---

## 🧠 Model Architecture

The CNN model consists of:

* Convolutional layers (feature extraction)
* MaxPooling layers (dimensionality reduction)
* Fully connected (Dense) layers
* Output layer with Softmax activation

### Key Layers:

* Conv2D (32 filters, 3×3)
* MaxPooling2D
* Conv2D (64 filters, 3×3)
* Dense layers
* Output layer (10 classes)

---

## 🏋️ Model Training

* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Epochs: 10
* Validation: Test set / validation split

---

## 📊 Results

* Achieved high classification accuracy (~98–99%)
* Model performs well on unseen test data

### Evaluation Metrics:

* Accuracy
* Loss

---

## 📈 Visualization

The project includes:

* Training vs Validation Loss
* Training vs Validation Accuracy

These plots help in:

* Detecting overfitting
* Understanding model convergence

---

## 🚀 How to Run

### Option 1: Google Colab

1. Open the notebook in Google Colab
2. Run all cells sequentially

### Option 2: Local Setup

```bash
pip install tensorflow matplotlib scikit-learn


```

Run the notebook using Jupyter:

```bash
jupyter notebook
```

---

## 📁 Project Structure

```
mnist-cnn-project/
│
├── mnist_google_colab.ipynb
├── README.md
```

---

## 🔍 Key Learnings

* Implemented CNN for image classification
* Understood importance of preprocessing and reshaping
* Learned model evaluation and visualization techniques
* Gained hands-on experience with TensorFlow/Keras

---

## 🚧 Future Improvements

* Add Dropout layers to reduce overfitting
* Perform hyperparameter tuning
* Implement confusion matrix for deeper evaluation
* Deploy model using Streamlit
* Extend to real-world image datasets

---

## 📌 Author

Shamima Yeasmin

---

## 💡 Conclusion

This project demonstrates a complete deep learning pipeline for image classification using CNNs. It serves as a strong foundation for more advanced computer vision tasks.

---
