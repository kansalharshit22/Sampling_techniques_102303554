# Sampling Assignment – Credit Card Fraud Detection

## Objective
The objective of this assignment is to understand the importance of **sampling techniques** when dealing with **highly imbalanced datasets** and to analyze how different sampling strategies affect the **performance of multiple machine learning models**.

---

## Dataset
- **Name:** `Creditcard_data.csv`
- **Source:**  
  https://github.com/AnjulaMehto/Sampling_Assignment/blob/main/Creditcard_data.csv
- **Description:**  
  The dataset is highly imbalanced.  
  The target variable **`Class`** represents:
  - `0` → Non-fraudulent transaction  
  - `1` → Fraudulent transaction  

---

## Steps Performed

### 1. Data Loading
- Loaded the dataset using **Pandas**
- Separated:
  - Features (`X`)
  - Target variable (`y` = `Class`)

---

### 2. Dataset Balancing
- Applied **Random Over Sampling** to handle class imbalance
- Converted the original imbalanced dataset into a **balanced dataset**

---

### 3. Sampling Techniques Applied
The following **five sampling techniques** were applied to the balanced dataset:

1. Simple Random Sampling  
2. Stratified Sampling  
3. Systematic Sampling  
4. Cluster Sampling  
5. Bootstrap Sampling  

Each sampling technique selects approximately **30%** of the balanced dataset.

---

### 4. Machine Learning Models Used
Each sampled dataset was used to train and evaluate the following models:

- **M1:** Logistic Regression  
- **M2:** Decision Tree Classifier  
- **M3:** Random Forest Classifier  
- **M4:** Naive Bayes  
- **M5:** Support Vector Machine (SVM)

---

## Output
- Model performance was evaluated for each combination of:
  - Sampling technique
  - Machine learning model
- The results highlight how different sampling strategies impact model accuracy on fraud detection tasks.

---

## Tools & Libraries
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn

---

## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook
2. Ensure required libraries are installed
3. Run all cells sequentially to reproduce results

---

## Results

Below is the screenshot showing the final results obtained from different sampling techniques and machine learning models:

![Results Screenshot](results.png)

---

## Author
*Harshit Kansal*  
*Roll No: 102303554*

