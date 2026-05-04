# Unbalanced Dataset Project – Neural Network Approach

## 📌 Overview

This project explores the problem of **class imbalance** in machine learning using a **Neural Network (NN)** model. The notebook demonstrates how unbalanced datasets can negatively affect model performance and evaluates different strategies to mitigate this issue.

The workflow includes:

* Data preprocessing
* Handling class imbalance
* Training a neural network
* Evaluating performance with appropriate metrics

---

## 🎯 Objectives

* Understand the impact of **imbalanced classes** on classification models
* Apply techniques to improve performance on minority classes
* Evaluate models using metrics beyond simple accuracy

---

## 📂 Project Structure

```
NN.ipynb    # Main notebook containing all code and experiments
```

---

## ⚙️ Methods and Workflow

### 1. Data Preparation

* Load and inspect dataset
* Analyze class distribution
* Split into training and testing sets

### 2. Handling Imbalance

The notebook explores common strategies such as:

* **Resampling techniques**

  * Oversampling (e.g., duplicating minority class)
  * Undersampling (reducing majority class)
* **Class weighting**

  * Assigning higher penalty to minority class errors

### 3. Model

* A **Neural Network classifier** is implemented
* Likely built using standard Python ML libraries (e.g., TensorFlow/Keras or PyTorch)
* Configurable architecture (layers, activation functions, etc.)

### 4. Training

* Model trained on processed dataset
* Comparison between:

  * Baseline (unbalanced data)
  * Improved approaches (after applying imbalance techniques)

### 5. Evaluation

Instead of relying only on accuracy, the notebook uses:

* Precision
* Recall
* F1-score
* Confusion matrix

These metrics are crucial when dealing with imbalanced datasets.

---

## 📊 Key Insights

* High accuracy can be misleading in imbalanced datasets
* Models tend to favor the majority class without correction
* Techniques like resampling and class weighting significantly improve minority class detection

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/MarcoPace00/Unbalanced_Dataset_project.git
cd Unbalanced_Dataset_project
```

2. Install dependencies (example):

```bash
pip install numpy pandas scikit-learn matplotlib seaborn tensorflow
```

3. Open the notebook:

```bash
jupyter notebook NN.ipynb
```

---

## 📌 Requirements

* Python 3.x
* Jupyter Notebook
* Common ML libraries:

  * NumPy
  * Pandas
  * Scikit-learn
  * Matplotlib / Seaborn
  * TensorFlow or PyTorch

---

## 🔮 Possible Improvements

* Try advanced imbalance methods (e.g., SMOTE, ADASYN)
* Hyperparameter tuning for the neural network
* Cross-validation for more robust evaluation
* Compare with other models (e.g., Random Forest, XGBoost)

---


## 👤 Author

* Marco Pace

---

## 💡 Notes

This project is a practical introduction to handling **imbalanced datasets**, a common issue in real-world applications such as fraud detection, medical diagnosis, and anomaly detection.
