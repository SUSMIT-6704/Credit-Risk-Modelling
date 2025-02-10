# Credit Risk Modeling (Classification Problem)

## Project Overview
This project focuses on **Credit Risk Modeling**, a classification problem that evaluates the likelihood of loan default. By analyzing financial and demographic data, the project predicts default probabilities, assigns credit scores, and calculates metrics to evaluate model performance. 

An interactive **Streamlit UI** has been developed to make predictions user-friendly and provide a seamless user experience.

---
![image](https://github.com/user-attachments/assets/2e7edfe4-8f97-4b49-8636-27a43bb1feb6)


## Key Features
- **Weight of Evidence (WOE)** and **IV Score** for categorical feature analysis.
- Tackled **class imbalance** using:
  - **Random Under-Sampling**
  - **SMOTETomek**
- Hyperparameter tuning with **Optuna**.
- Evaluated model performance using:
  - **Rank Order**: 85.88% found at Decile 8
  - **AUC**: 0.98
  - **Gini Coefficient**: 0.96
- Built an interactive **Streamlit UI** for predictions and insights.

---

## Technologies and Tools Used
- **Programming Language**: Python
- **Libraries**:
  - **scikit-learn**: Model building and evaluation
  - **imbalanced-learn**: SMOTETomek and Random Under-Sampling
  - **Optuna**: Hyperparameter tuning
  - **Pandas & NumPy**: Data processing and analysis
  - **Matplotlib & Seaborn**: Data visualization
- **Framework**: Streamlit for UI development
- **Models Used**:
  - Logistic Regression
  - Random Forest
  - XGBoost

---

## Project Workflow
### 1. Data Preprocessing
- Analyzed data for missing values and outliers.
- Engineered features such as WOE and IV Score.

### 2. Handling Class Imbalance
- Implemented **Random Under-Sampling** and **SMOTETomek** techniques to balance the dataset.

### 3. Model Building
- Built and compared classification models (Logistic Regression, Random Forest, and XGBoost).
- Tuned hyperparameters using **Optuna** for improved accuracy.

### 4. Model Evaluation
- **Rank Order**: Identified distribution of default probabilities.
- **AUC**: Achieved 0.98, indicating excellent performance.
- **Gini Coefficient**: Scored 0.96, showcasing model reliability.

### 5. Interactive UI
- Created a **Streamlit app** to:
  - Accept user input for predictions.
  - Display default probability, credit score, and rating.

---

## How to Run the Project
### Prerequisites
1. Install Python (>=3.8).
2. Clone the repository:
   ```bash
   git clone https://github.com/PrabhudattaPatra/credit-risk-model.git
   cd credit-risk-model
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Requirements File
The `requirements.txt` file includes:
```
pandas==2.2.3
numpy==2.0.2
joblib==1.4.2
streamlit==1.41.1
scikit-learn==1.5.2
xgboost==1.6.2
```

### Run the Streamlit App
```bash
streamlit run app.py
```

### Access the Live App
[Streamlit App](https://prabhudatta-credit-risk-model.streamlit.app/)

---

## Project Results
- **Rank Order**: 85.88% at Decile 8
- **AUC**: 0.98
- **Gini Coefficient**: 0.96

---

## References
A special thanks to **Codebasics** and **Dhaval Patel Sir** for their exceptional tutorials and step-by-step guidance. 🙏

---

## Feedback
Your feedback and suggestions are highly appreciated! Feel free to contribute or open issues in this repository.

---

