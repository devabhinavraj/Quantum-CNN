# Hybrid Quantum Convolutional Neural Network (HQCNN)

Hybrid Quantum Convolutional Neural Network (HQCNN) is a deep learning framework that integrates classical Convolutional Neural Networks (CNNs) with quantum computing circuits to enhance feature extraction and classification performance.

The goal of this project is to explore hybrid quantum-classical machine learning models that combine the strengths of traditional deep learning with the computational capabilities of quantum circuits.

---

# Overview

Deep learning models such as CNNs are highly effective for tasks like image classification and pattern recognition. Quantum computing introduces new ways of representing and processing information using quantum states.

Hybrid Quantum CNNs combine these two paradigms:

- Classical CNN layers extract spatial features from data.
- Extracted features are encoded into quantum states.
- Quantum circuits process these features using parameterized quantum gates.
- The measured results are used by classical layers for final classification.

This hybrid approach aims to explore potential improvements in representation learning and computational efficiency.

---

# Key Features

- Hybrid Quantum–Classical neural network architecture
- Integration of CNN layers with quantum circuits
- Modular and extensible code structure
- Suitable for quantum machine learning research
- Supports image classification tasks
- Compatible with quantum frameworks like PennyLane and Qiskit

---

# Architecture

The HQCNN model consists of three main stages:

### 1. Classical Feature Extraction

The CNN layers extract features from the input data.

Components include:

- Convolution layers
- Activation functions (ReLU)
- Pooling layers

These layers learn spatial patterns from the dataset.

---

### 2. Quantum Processing Layer

The extracted classical features are encoded into quantum states.

Steps include:

- Feature encoding
- Parameterized quantum circuits
- Quantum gate operations
- Entanglement between qubits
- Measurement of quantum states

Quantum circuits operate in a high-dimensional Hilbert space which can potentially provide richer representations.

---

### 3. Classical Classification Layer

After measurement, the quantum outputs are passed to classical fully connected layers for classification.

Components include:

- Fully connected layers
- Activation functions
- Softmax or sigmoid output layer

---

---

# Technologies Used

- Python
- PyTorch or TensorFlow
- PennyLane
- Qiskit
- NumPy
- Matplotlib

---

# Installation

Clone the repository:
https://github.com/devabhinavraj/Quantum-CNN/blob/main/Breast-Cancer-QCNN.ipynb
