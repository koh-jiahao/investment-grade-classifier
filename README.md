# Investment Grade Classifier
This repository contains a Jupyter Notebook that classifies corporate companies as either:

- Investment Grade
- Non-Investment Grade (Junk)

based on financial and categorical indicators.

---

<h2>📌 Project Overview</h2>

🎯 **Objective**

To build and compare machine learning models that classify corporate credit rating tiers using labeled data. The two classifiers used are:

🔹 **1. Naive Bayes Classifier**

  A probabilistic classifier suitable for high-dimensional data and categorical variables.

  

🔹 **2. Decision Tree Classifier** (with hyperparameter tuning and cross-validation)

- Criterion: entropy (for information gain)

- Hyperparameter: max_depth optimized using 10-fold cross-validation

- Best depth selected based on highest cross-validation score


<h2>📊 Evaluation Metrics</h2>

Both models are evaluated using:

- Confusion Matrix

- Classification Report: Precision, Recall, F1-score

- Cross-Validation Accuracy


<h2>✅ Results Summary</h2>

The Decision Tree model, when optimized via cross-validation, generally performs better than the Naive Bayes model in classification accuracy and F1-score.

Optimal tree depth was found by plotting cross-validated scores for depths 2–29.


---
<h2>📁 Files</h2>

- **IVgrade_classification.ipynb**: Main notebook with all data processing, model training, evaluation, and plots.

- **requirements.txt**: Python dependencies list.

- **corporateCreditRatingWithFinancialRatios.csv**: Data file


---
<h1>🧪 How to Use</h1>

1. Clone the repository:
    ```bash
    git clone https://github.com/koh-jiahao/Investment-Grade-Classifier.git
    cd credit-grade-classification


2. Install dependencies:
    ```bash
    pip install -r requirements.txt


3. Launch the notebook:
    ```bash
    jupyter notebook


4. Open the .ipynb file and run the cells.
