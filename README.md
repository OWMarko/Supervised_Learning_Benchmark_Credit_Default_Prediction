# Supervised Learning Benchmark : Credit Risk Analysis

## Academic Integrity Notice
> The full source code (`.R` scripts) and the dataset are **not included** in this repository. 
> This project is part of an active university curriculum at **Université Côte d'Azur**. To prevent plagiarism and preserve the integrity of the subject for future students, only the methodology and results are presented here.

## Project Overview
This project benchmarks multiple supervised learning algorithms to predict credit default risks. The objective was to compare model performance on unbalanced data, focusing on the trade-off between **Sensitivity** (detecting defaults) and **Specificity** (avoiding false alarms).

##  Methodology
* **Preprocessing :** Imputation of missing values, outlier removal, and normalization.
* **Models Compared :**
    1. Decision Trees (C5.0 & CART)
    2. Random Forest
    3. Naïve Bayes
    4. K-Nearest Neighbors (KNN)
    5. Neural Networks (Single hidden layer)
* **Evaluation Metrics :** ROC Curves, AUC (Area Under Curve), and Confusion Matrices.

## Key Results
* **Best Performer :** **Random Forest** achieved the highest AUC and stability, effectively handling non-linear patterns.
* **Fastest :** **Naïve Bayes** offered the quickest training time but with lower precision on complex cases.
* **Critical Finding :** The analysis highlighted that maximizing global accuracy is insufficient; adjusting the classification threshold was necessary to minimize financial risk (False Negatives).

## Tech Stack
* **Language:** R
* **Libraries :** `caret`, `randomForest`, `pROC`, `e1071`, `nnet`.

---
*For any questions regarding the benchmarking methodology or the theoretical report, feel free to contact me.*

---
*For any questions regarding the benchmarking methodology or the theoretical report, feel free to contact me.*
