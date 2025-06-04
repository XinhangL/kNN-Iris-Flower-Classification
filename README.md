# 🌸 Iris Flower Classification using k-Nearest Neighbors (k-NN)

This notebook implements a k-NN classifier to identify species of Iris flowers based on sepal and petal measurements.  
The project is a classic ML exercise and a great demonstration of data preprocessing, model tuning, and evaluation.

---

## 📌 Project Overview

- **Dataset**: Iris flower dataset (`Iris.csv`)
- **Goal**: Classify iris species based on four numerical features
- **Model**: k-Nearest Neighbors (k-NN) from `sklearn`
- **Optimization**: Tune `k` from 1 to 29 and evaluate performance

---

## 🧠 Key Techniques

- Data loading and slicing with `pandas`
- Train/test splitting using `train_test_split`
- Feature scaling with `StandardScaler`
- Model training and accuracy analysis for various values of `k`
- Evaluation using `.score()`, `accuracy_score`, `confusion_matrix`

---

## 📁 Files

| File                      | Description                        |
|---------------------------|------------------------------------|
| `Script KNN Iris.ipynb`   | Main notebook                      |
| `Iris.csv`                | Input dataset (standard UCI format)|
| `README.md`               | Project overview and instructions  |

---

## 🚀 How to Run

1. Place `Iris.csv` in the same folder as the notebook
2. Open the notebook in Jupyter or VS Code
3. Run all cells to view the training process and performance scores

---

## 📈 Output

- Train and test accuracy across different `k` values
- Best `k` based on test accuracy
- Final model evaluation report

---

## 🧰 Tools Used

- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn

---

This notebook is perfect for showcasing my understanding of supervised classification, model selection, and performance evaluation.
