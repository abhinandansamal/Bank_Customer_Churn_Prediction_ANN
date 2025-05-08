# Bank_Customer_Churn_Prediction_ANN

This is an interactive **Streamlit web application** that predicts whether a customer is likely to churn based on demographic and account-related inputs. The app leverages a pre-trained Artificial Neural Network (`model.h5`) and applies preprocessing steps using pre-fitted encoders and a scaler.

---

## 🚀 Features

- Predict customer churn probability using a trained ANN model.
- Input interface for credit score, age, geography, gender, account balance, and more.
- One-hot encoding and label encoding applied with saved encoders.
- Feature scaling using a pre-fitted `StandardScaler`.
- Scalable and lightweight Streamlit interface.

---

## 🗂️ Project Structure

    ├── data/
    │   └── Churn_Modelling.csv
    ├── logs/
    ├── model/
    │   └── model.h5
    ├── notebooks/
    │   ├── experiments.ipynb
    │   └── prediction.ipynb
    ├── pkl/
    ├── venv/
    ├── app.py
    ├── requirements.txt
    ├── README.md
    └── LICENSE


---

## 🧪 Technologies Used

- Python
- Streamlit
- TensorFlow / Keras
- Pandas, NumPy
- Scikit-learn (LabelEncoder, OneHotEncoder, StandardScaler)
- Pickle

---

## How to run?

### Step 1:

**Clone the repository**
   ```bash
   git clone https://github.com/your-username/Bank_Customer_Churn_Prediction_ANN.git
   cd Bank_Customer_Churn_Prediction_ANN
   ```


### Step 2:

**Create virtual environment**

```bash
conda create -p venv python==3.11 -y
```

### Step 3:

**Activate virtual environment**

```bash
conda activate venv
```

### Step 4:

**Install the dependencies**

```bash
pip install -r requirements.txt
```

### Step 5:

**Run the Streamlit app**

```bash
streamlit run app.py
```
---

## 📌 How to Use
1. Enter values for the customer's profile and account features via the Streamlit UI.

2. The app will:
    - Apply necessary encodings and scaling.
    - Predict the churn probability using the loaded ANN model.

3. The result will indicate whether the customer is likely to churn or not.

---

## ✨ Acknowledgements
This project is part of a personal initiative to build real-time, AI-driven customer analytics solutions using deep learning and modern Python tools.