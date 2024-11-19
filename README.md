# 😷 Face Mask Detection using Convolutional Neural Networks (CNN)

Welcome to the **Face Mask Detection** project! This repository showcases how to build a machine learning model to detect whether a person is wearing a face mask or not using **Convolutional Neural Networks (CNN)**. 🧠

---

## 📌 Project Details

- **Author**: [Syed Muhammad Ebad](https://www.kaggle.com/syedmuhammadebad)
- **Email**: [mohammadebad1@hotmail.com](mailto:mohammadebad1@hotmail.com)
- **Dataset**: [Face Mask Detection Dataset](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset/data)
- **Frameworks Used**: TensorFlow/Keras, Matplotlib, Seaborn, NumPy
- **Goal**: To classify images into two categories:
  - ✅ With Mask
  - ❌ Without Mask

---

## 🗂️ Dataset Structure

The dataset is divided into two folders:
1. Data with masked face images
2. Data without mask face images


---

## 🛠️ Key Features

1. **Data Visualization**: Displayed sample images of both classes and analyzed class distributions 📊.
2. **Data Augmentation**: Implemented transformations such as rotation, zooming, and flipping to improve model generalization ✨.
3. **CNN Architecture**: Built a CNN model with layers for convolution, pooling, and dropout to extract features and avoid overfitting 🧩.
4. **Training and Validation**: Achieved a validation accuracy of around **93%** with early stopping to prevent overfitting 🎯.
5. **Evaluation**: Used a confusion matrix and classification report for model performance analysis 📈.

---

## 🚀 Project Workflow

### 1. **Importing Libraries**
Imported necessary libraries such as TensorFlow, NumPy, Matplotlib, and Seaborn. ✅

### 2. **Data Visualization**
Visualized images from both categories using Matplotlib to understand the dataset structure. 🖼️

### 3. **Data Preprocessing**
Prepared the dataset using `ImageDataGenerator`:
- Rescaled pixel values to [0, 1].
- Applied data augmentation like rotation, zoom, and flips.
- Split data into **training** (80%) and **validation** (20%). 📂

### 4. **Model Architecture**
Built the CNN model with the following layers:
- 3 Convolution + Pooling layers for feature extraction.
- Fully connected layers with **Dropout** for regularization.
- Final layer with a **Sigmoid** activation for binary classification. 🧱

### 5. **Training**
Trained the model for **20 epochs** with **early stopping** to achieve the best results without overfitting. 🏋️‍♂️

### 6. **Evaluation**
Evaluated model performance using:
- Confusion Matrix 📦
- Classification Report 🗂️
- Accuracy and Loss plots 📊

---

## 📈 Results

- **Validation Accuracy**: ~93% 🎉
- **Confusion Matrix**: 

| Actual / Predicted | Without Mask | With Mask |
|--------------------|--------------|-----------|
| Without Mask       | Excellent 🔥 | Minimal Misclassifications ⚠️ |
| With Mask          | Minimal Misclassifications ⚠️ | Excellent 🔥 |

---

## 🖼️ Visualization

### Class Distribution


### Training History


---

## 📋 To-Do / Future Work

- 🔍 Experiment with advanced architectures like **ResNet** or **MobileNet** for better accuracy.
- 🔄 Fine-tune hyperparameters such as learning rate, batch size, and dropout rates.
- 🌐 Deploy the model as a web app or mobile app for real-world applications.

---

### 📬 Have feedback or questions? Feel free to email me or connect on Linkedin. 🙌

