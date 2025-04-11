# 🧠 Brain Stroke Prediction

This repository contains a university project aimed at predicting brain stroke occurrences using machine learning techniques. The project has two main objectives:

1. **Paper Replication**: Reproduce the methodologies and findings of the research paper *"Stroke Risk Prediction with Machine Learning Techniques"*.
2. **Best Practices Implementation**: Develop an alternative version employing contemporary best practices in machine learning and data analysis.

---

## 📁 Project Structure

- `NAML_project_paper_replica_A.ipynb`: Notebook replicating the original research paper's methodology.
- `NAML_project_best_practice_B.ipynb`: Notebook implementing best practices for improved model performance and robustness.
- `report/`: Contains the comprehensive project report detailing methodologies, experiments, and results.
- `images/`: Directory for visualizations and plots used in the notebooks and report.
- `resources/`: Additional resources and references utilized in the project.

---

## ⚠️ Known Issue in Paper Replication

**Important**: In the `NAML_project_paper_replica_A.ipynb` notebook, SMOTE (Synthetic Minority Over-sampling Technique) is applied to both the training and test datasets.  
This is a **methodological error** that leads to **data leakage** and overly optimistic model performance.  
To see a corrected version using best practices, refer to the `NAML_project_best_practice_B.ipynb` notebook, where SMOTE is correctly applied **only to the training set**.

---

## 📊 Key Highlights

- **Dataset**: Publicly available stroke prediction dataset from Kaggle.
- **Algorithms Implemented**:
  - Random Forest
  - Naive Bayes
  - Logistic Regression
  - Support Vector Machines (SVM)
- **Evaluation Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Area Under the Curve (AUC)

---

## 🚀 Getting Started

To explore and run the notebooks:

1. **Clone the repository**:
     ```bash
     git clone https://github.com/AlbertoEusebio/Brain-Stroke-Prediction.git
   ```
2. Navigate to the project directory:
    ```bash
     cd Brain-Stroke-Prediction
   ```
3. Install the required dependencies:
    ```bash
     pip install -r requirements.txt
   ```
4. Launch Jupyter Notebook:
    ```bash
     jupyter notebook
   ```
5. Open and run the desired notebook:
  *  For paper replication: NAML_project_paper_replica_A.ipynb
  *  For best practices: NAML_project_best_practice_B.ipynb

---

## 📄 Report
A detailed report outlining the project's methodology, experiments, results, and conclusions is available in the report/ directory.

---

## 👥 Team
Sara Cavallini

Alberto Eusebio

University: Politecnico di Milano
Course: Numerical Analysis for Machine Learning (NAML)
