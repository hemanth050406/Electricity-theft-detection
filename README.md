# ⚡ Smart Energy Theft Detection using Machine Learning

This project leverages machine learning to detect electricity theft using smart meter data. It involves preprocessing datasets, training a Random Forest model, evaluating its performance, and detecting anomalies. A simple Streamlit UI allows users to interact with the system for theft prediction.

---

## How It Works

1. **Data Preprocessing**
   - Cleans the raw smart meter data
   - Handles missing values and feature scaling
   - Splits data into train/test sets

2. **Model Training**
   - Train the models on the data

3. **Model Evaluation** 
   - Calculates accuracy, precision, recall, F1-score
   - Confusion matrix and other classification metrics

4. **Anomaly Detection**
   - Uses trained model to detect energy theft
   - Returns whether a user is “Normal” or “Suspected Theft”

5. **Model Selection**
   - Select the model which has more accuracy

---

## Sample Output (Streamlit UI)

* Upload smart meter data (CSV)
* Displays prediction (Normal / Theft)
* Confidence score for each sample

---

## 📌 Dependencies

Main packages used:

* `pandas`, `numpy`
* `scikit-learn`
* `matplotlib`, `seaborn`
* `joblib`

---

## 📈 Model Selection

* **Decision Tree**

---

## 📄 License

This project is open-source and available.