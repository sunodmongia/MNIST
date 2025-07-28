# 🔢 MNIST Handwritten Digit Classification

## 📌 Overview

This project focuses on classifying handwritten digits (0–9) from the **MNIST dataset** using machine learning and deep learning techniques.

- 📊 **Dataset**: The [MNIST dataset] consists of 70,000 grayscale images of handwritten digits (28x28 pixels). This dataset is created by high school students and employees of US Census Bureau.
- 🧠 **Goal**: Build an accurate classifier that can recognize digits from 0 to 9.
- ⚙️ **Approach**: Multiple models were explored — from Logistic Regression to deep learning using CNNs — with performance compared using accuracy and confusion matrices.

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/3b35bd58-e8ce-4a68-9931-5c94a69a06eb" />

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


---


## 💾 Dataset Description

| Feature         | Description                            |
| --------------- | -------------------------------------- |
| `image (28x28)` | Grayscale image of a handwritten digit |
| `label`         | True digit (0–9)                       |

🎯 Target: The digit label (0–9) for each image.


---


🤖 Models Used
Multiple models were trained and evaluated using cross-validation and test accuracy:

| Model                  | Cross Validation | Training Time | Remarks         |
| -----------------------| ---------------- | ------------- | --------------- |
| SGDClassifier          |     87.54%       | Fast          | Less Accurate   |
| RandomForestClassifier |  ```to update``` | Moderate      | Fast + Moderate |
| SVC (OvO) (RBF Kernel) |  ```to update``` | Slow          | Accurate        |
| SVC (OvR) (RBF Kernel) |  ```to update``` | Slow          | Highly accurate |

# Model used: SVC (OvR) (rbf Kernel)


---

📊 Evaluation Metrics
  - Accuracy Score
  - Confusion Matrix
  - Classification Report: [[Precision, Recall, F1-Score, ROC, AUC]]
  - Curve: [[Precision/Recall curve, ROC curve, ROC_AUC curve]]
  - Visualizations of sample predictions

```more to add```
 
---

🧹 Data Preprocessing
1. StandardScaler:
   - Standard Scaling up data to increase its accuracy for the model

2. Train-Test Split
  - Training Set: 56,000 samples
  - Testing Set: 14,000 samples
  - Using ```train_test_split``` for spliting data and stratified using stratify=y (hyperparameter).

Stratified sampling used for balanced class distribution.

```more to add```

---

# How to Run

1. Clone the Repository:
   ```git clone https://github.com/yourusername/mnist.git```

2. Setup Environment:
   ```python -m venv venv```
   ```source venv/bin/activate```

3. Install all dependencies using:
  ```pip install -r requirements.txt```

