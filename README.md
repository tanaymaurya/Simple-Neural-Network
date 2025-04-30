# Neural Network from Scratch – MNIST Digit Classifier

This project implements a **simple feedforward neural network from scratch using only NumPy**, trained on the MNIST handwritten digit dataset.

🎯 **Goal**: Learn how neural networks work internally by building one from scratch without using machine learning libraries like TensorFlow or PyTorch.

---

## 🔍 Highlights

- **Achieved 94.79% test accuracy** on the MNIST dataset
- Implemented:
  - Forward propagation
  - Backpropagation
  - Mini-batch gradient descent
  - ReLU and Softmax activations
  - Cross Entropy loss
- No machine learning libraries used — **only NumPy**

---

## 📊 Dataset

- **MNIST**: 28×28 grayscale images of handwritten digits (0–9)
- Input size: 784 (flattened 28×28 images)
- Dataset loaded via `tensorflow.keras.datasets` (only for data loading)

---

## 🧠 Network Architecture

- Input layer: 784 neurons
- Hidden layers: 1–2 layers with ReLU activation
- Output layer: 10 neurons with Softmax

---

## 📈 Results

- **Test Accuracy**: `94.79%`
- Trained using **Mini-Batch Gradient Descent** with batch size of 64
- 10–20 epochs depending on hyperparameters

---

## 🛠 Technologies Used

- Python
- NumPy
- Google Colab

---

## 📁 Files

- `Neural_network_from_scratch.ipynb`: Complete code and training logs


---

## 🚀 Running the Code

You can run this project using Google Colab or any Python environment:

```bash
pip install numpy
