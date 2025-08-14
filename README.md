# Automated-Classification-of-Iris-Flower-Species


## Project Overview

This project demonstrates how to use a **Decision Tree Classifier** to predict the species of **Iris flowers** based on their measurements.

The goal is to classify an Iris flower into one of three species:

* *Setosa*
* *Versicolor*
* *Virginica*

using the famous **Iris dataset** included in the `scikit-learn` library.

---

## 🛠 Workflow

1. **Loading the Dataset**

   * The built-in Iris dataset from `scikit-learn` is loaded.

2. **Data Preparation**

   * Features: Sepal length, Sepal width, Petal length, Petal width
   * Target: Species name (mapped from numeric labels for readability)

3. **Data Splitting**

   * Dataset is split into **training** and **testing** sets.

4. **Model Training**

   * A **Decision Tree Classifier** is trained on the training data.

5. **Model Evaluation**

   * Accuracy score and classification report are generated for test data.

6. **Prediction**

   * Model predicts the species of a new, unseen Iris flower from its measurements.

---

## 📦 Requirements

* Python **3.6+**
* scikit-learn
* pandas

Install the required libraries using:

```bash
pip install scikit-learn pandas
```

---

## ▶️ How to Run

1. **Clone the repository**

```bash
git clone https://github.com/Snehanshu03/Automated-Classification-of-Iris-Flower-Species.git
cd iris-decision-tree
```

2. **Run the script**

```bash
python iris_decision_tree.py
```

3. **View Output**

   * Accuracy score of the model
   * Classification report
   * Prediction for a new flower’s measurements

---

##  Output

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


