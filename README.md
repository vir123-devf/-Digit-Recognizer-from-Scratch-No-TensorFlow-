# 🧠 Digit Recognizer from Scratch (No TensorFlow)

This project demonstrates how to build a **handwritten digit recognizer** from scratch using only NumPy and basic Python libraries — no high-level deep learning frameworks like TensorFlow or PyTorch.

> **Goal:** Classify digits (0–9) from the [MNIST dataset](https://www.kaggle.com/c/digit-recognizer/data) using a simple neural network built from the ground up.

---

## 🔍 Overview

This notebook walks through the full pipeline of creating a neural network, including:

- 🧹 Data Preprocessing  
- 🏗️ Building a feedforward neural network (1 hidden layer)  
- 📉 Implementing backpropagation  
- 🧠 Training using gradient descent  
- 📊 Evaluating model accuracy  

---

## 📁 Files

- `digit-recognizer-from-scratch.ipynb` — main notebook with all the code and explanations.  
- `train.csv` — training data (download from Kaggle).  
- `test.csv` — test data (optional: for evaluating model predictions).  

---

## 🧰 Dependencies

- Python 3.8+
- NumPy
- Pandas
- Matplotlib (for visualizations)

Install them using:

```bash
pip install numpy pandas matplotlib
```

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/vir123-devf/digit-recognizer-from-scratch.git
   cd digit-recognizer-from-scratch
   ```

2. Open the notebook:
   ```bash
   jupyter notebook digit-recognizer-from-scratch.ipynb
   ```

3. Make sure `train.csv` is in the same folder, or update the path in the notebook.

4. Run all cells to train and evaluate the model.

---

## 📈 Sample Output

- Training Accuracy: ~85–92% (depending on hyperparameters)
- No ML libraries used — fully custom gradient descent implementation

---

## 💡 What You’ll Learn

- How neural networks work internally  
- How to implement forward and backward propagation manually  
- Basics of gradient descent optimization  
- MNIST digit classification from raw pixel data  

