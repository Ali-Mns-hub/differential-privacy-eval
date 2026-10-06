# Data Setup

This project uses three different datasets to evaluate Differential Privacy (DP):

1.  **Synthetic Data:** Generated internally using `numpy` for the Linear Regression evaluation[cite: 88, 110].
2.  **Iris Dataset:** Loaded directly via `sklearn.datasets.load_iris()` for the GaussianNB evaluation[cite: 93, 112].
3.  **Diabetes Dataset:** Used for the Logistic Regression evaluation[cite: 91, 111].
    *   **File needed:** `diabetes.csv`[cite: 91, 111]
    *   Place this file directly inside the `data/` folder.
