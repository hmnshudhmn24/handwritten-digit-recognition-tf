# ✍️ Handwritten Digit Recognition

This project implements a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset using TensorFlow.

## 📚 Dataset

- MNIST: 60,000 training and 10,000 testing grayscale images of handwritten digits (0–9).

## 🧠 Model Architecture

- Conv2D ➝ MaxPooling2D ➝ Conv2D ➝ MaxPooling2D ➝ Flatten ➝ Dense ➝ Dense (Softmax)

## 📦 Requirements

```bash
pip install tensorflow matplotlib
```

## 🚀 How to Run

```bash
python digit_classifier.py
```

## 📈 Output

Displays accuracy and loss graphs and evaluates the trained model on test data.

## 📁 Files

- `digit_classifier.py` — Main model training and evaluation code.
- `README.md` — Project documentation.