# AIML--TASK--10
KNN – Handwritten Digit Classification
# Handwritten Digit Classification using KNN

This project demonstrates handwritten digit classification using the **K-Nearest Neighbors (KNN)** algorithm on the **Digits dataset** from `scikit-learn`. The goal is to classify digits (0–9) based on pixel intensity values.

---

## Dataset Description
- Dataset: Digits Dataset (sklearn)
- Total samples: 1797
- Number of classes: 10 (digits 0–9)
- Features: 64 (8×8 pixel values)
- Target: Digit labels (0–9)

---

##  Machine Learning Workflow

1. Load the digits dataset and inspect the shape of features and labels.
2. Visualize sample digit images to verify correct labeling.
3. Split the dataset into training and testing sets.
4. Apply feature scaling using `StandardScaler` (important for KNN).
5. Train a KNN classifier with **K = 3**.
6. Evaluate the model using **accuracy score**.
7. Experiment with different K values (3, 5, 7, 9).
8. Plot **Accuracy vs K** to find the optimal value.
9. Generate a **confusion matrix** to analyze misclassifications.
10. Display test images along with predicted labels.

---

##  Technologies Used
- Python
- NumPy
- Matplotlib
- Scikit-learn

---

##  Model Evaluation

### Accuracy vs K
The accuracy is evaluated for different values of K to select the best-performing model.

![Accuracy vs K](images/accuracy_vs_k.png)

---

### Confusion Matrix
The confusion matrix provides a detailed breakdown of correct and incorrect predictions for each digit class.

![Confusion Matrix](images/confusion_matrix.png)

---

##  Results
- KNN achieved high accuracy on the test dataset.
- Feature scaling significantly improved performance.
- Optimal K was selected based on the accuracy vs K plot.

---

##  How to Run the Project

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/knn-digit-classification.git
