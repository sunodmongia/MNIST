# 🔢 MNIST Handwritten Digit Classification

## 📌 Overview

This project focuses on classifying handwritten digits (0–9) from the **MNIST dataset** using machine learning and deep learning techniques.

- 📊 **Dataset**: The [MNIST dataset] consists of 70,000 grayscale images of handwritten digits (28x28 pixels). This dataset is created by high school students and employees of US Census Bureau.
- 🧠 **Goal**: Build an accurate classifier that can recognize digits from 0 to 9.
- ⚙️ **Approach**: Multiple models were explored — from Logistic Regression to deep learning using CNNs — with performance compared using accuracy and confusion matrices.

<img width="600" alt="mnist-sample" src="https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png" />

---

## 📚 Libraries Used

The following Python libraries were used for data handling, model training, and evaluation:

| Library         | Purpose                                  |
|-----------------|------------------------------------------|
| `numpy`         | Array operations and preprocessing       |
| `pandas`        | Data structuring and analysis            |
| `matplotlib`    | Data visualization                       |
| `seaborn`       | Heatmaps and confusion matrix plots      |
| `scikit-learn`  | ML models, preprocessing, and evaluation |
| `joblib`        | Saving/loading trained models            |
| `jupyter`       | Notebook development and visualization   |

📌 Install all dependencies using:
```bash
pip install -r requirements.txt

