# Heart Failure Prediction Using Machine Learning

This project uses machine learning to predict the presence of heart disease based on clinical data from 918 patients with 12 features. A K-Nearest Neighbors (KNN) classifier is implemented and optimized using hyperparameter tuning with Optuna to achieve strong predictive performance.

---

## Project Highlights

- Developed a KNN classification model for heart disease prediction.
- Performed data cleaning, preprocessing, and one-hot encoding for categorical variables.
- Hyperparameter tuning (k value, weight type) with Optuna for model optimization.
- Achieved **91% accuracy** and a **weighted F1-score of 0.91** on a held-out test set of 184 patients.
- Evaluated the model using precision, recall, F1-score, confusion matrix, and ROC-AUC metrics.
- Implemented using Python libraries: `scikit-learn`, `pandas`, `matplotlib`, and `Optuna`.

---

## Dataset

- The dataset consists of clinical data for 918 patients with 12 features related to heart health.
- It contains attributes such as age, sex, chest pain type, blood pressure, cholesterol, and others.
- File: `heart.csv`

---

## Installation

1. Clone the repository:
   <ul>
      <li>git clone https://github.com/your-username/heart-failure-prediction.git
      <li>cd heart-failure-prediction
   </ul>

3. Install required Python packages:
   <ul>
      <li>pip install -r requirements.txt
   </ul>




## Results

- **Accuracy:** 91%  
- **Weighted F1-score:** 0.91  
- Balanced precision and recall across both classes (healthy and diseased).

These results demonstrate the robustness and reliability of the KNN model for heart disease prediction on clinical data.

