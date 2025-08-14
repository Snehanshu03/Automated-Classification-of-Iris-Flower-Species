# Automated-Classification-of-Iris-Flower-Species



## 📌 Project Overview

This project demonstrates how to use a **Decision Tree Classifier** to predict the species of **Iris flowers** based on their measurements.

The objective is to classify an Iris flower into one of three species:

* *Setosa*
* *Versicolor*
* *Virginica*

using the well-known **Iris dataset** included in the `scikit-learn` library.

---

## 🛠 Workflow

1. **Loading the Dataset**

   * Use `scikit-learn` to load the built-in Iris dataset.

2. **Data Preparation**

   * Features: Sepal length, Sepal width, Petal length, Petal width
   * Target: Species name (mapped from numeric labels).

3. **Data Splitting**

   * Train/Test split for evaluation.

4. **Model Training**

   * Train a **Decision Tree Classifier** on the training data.

5. **Model Evaluation**

   * Accuracy score and classification report for performance metrics.

6. **Prediction**

   * Predict the species of a new Iris flower from its measurements.

---

## 📦 Requirements

* Python **3.6+**
* scikit-learn
* pandas

Install the dependencies (for **Jupyter Notebook** or **local environment**):

```bash
pip install scikit-learn pandas
```

For **Google Colab**, you can run:

```python
!pip install scikit-learn pandas
```

---

## ▶️ How to Run

### **🔹 Option 1: Google Colab**

1. Open the notebook in Colab:
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/iris-decision-tree/blob/main/Iris_Decision_Tree.ipynb)

2. Run all cells (`Runtime → Run all`).

---

### **🔹 Option 2: Jupyter Notebook (Local)**

1. Clone the repository:

```bash
git clone https://github.com/your-username/iris-decision-tree.git
cd iris-decision-tree
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

3. Open `Iris_Decision_Tree.ipynb` and run all cells.

---

## 📊 Output

```
Accuracy on Test Data: 1.00

Classification Report:
              precision    recall  f1-score   support

      setosa       1.00      1.00      1.00        10
  versicolor       1.00      1.00      1.00         9
   virginica       1.00      1.00      1.00        11

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30
```

---

## 📚 Dataset Reference

The Iris dataset was first introduced by **Ronald A. Fisher (1936)** and is a classic dataset for pattern recognition.

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use and modify it.

---



