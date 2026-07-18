# Covid19-PneumoniaDetection

A Computer Vision project that detects **Pneumonia** from **Chest X-ray images** using a **Convolutional Neural Network (CNN)**. The model classifies X-ray images as **Normal** or **Pneumonia**, assisting in the early detection of lung infections.

## 📌 Overview

This project applies deep learning techniques to classify chest X-ray images into two categories: **Normal** and **Pneumonia**. The model is trained on labeled medical images and can predict the class of new X-ray images with high accuracy.

## 🚀 Features

- Binary classification of Chest X-ray images
- Image preprocessing and normalization
- CNN-based deep learning model
- Predicts Normal or Pneumonia
- Easy-to-use inference on new X-ray images

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

## 📂 Project Structure

```text
Pneumonia-Detection/
│── dataset/
│   ├── train/
│   ├── val/
│   └── test/
│── models/
│── pneumonia_detection.py
│── requirements.txt
│── README.md
```

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/Pneumonia-Detection.git
```

2. Navigate to the project folder

```bash
cd Pneumonia-Detection
```

3. Install the required dependencies

```bash
pip install -r requirements.txt
```

4. Run the project

```bash
python pneumonia_detection.py
```

## 🔍 How It Works

1. Load the Chest X-ray dataset.
2. Preprocess images by resizing and normalizing them.
3. Train the CNN model using labeled X-ray images.
4. Validate and test the trained model.
5. Predict whether a new X-ray image is **Normal** or **Pneumonia**.

## 📊 Results

- Successfully classifies Chest X-ray images into **Normal** and **Pneumonia**.
- Demonstrates the effectiveness of CNNs for medical image classification.
- Helps understand the role of AI in healthcare diagnostics.

## 📚 Learning Outcomes

- Medical image preprocessing
- Convolutional Neural Networks (CNNs)
- Image classification using deep learning
- Model evaluation and prediction
- Deep learning workflow using TensorFlow/Keras

## 🔮 Future Improvements

- Use transfer learning models such as ResNet50 or EfficientNet.
- Add Grad-CAM visualizations for model explainability.
- Build a web application using Flask or Streamlit.
- Extend the model to classify multiple lung diseases.
- Improve performance with larger and more diverse datasets.

## 👩‍💻 Author

**Adina Isran**

B.Tech in Computer Science (AI & ML)
