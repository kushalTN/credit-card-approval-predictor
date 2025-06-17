# credit-card-approval-predictor
This project is a complete end-to-end machine learning application built using Python and Streamlit to predict whether a credit card application will be approved or denied based on applicant data. It simulates a real-world deployment environment with a clean web interface and trained ML model.

# 💳 Credit Card Approval Prediction

A real-world **machine learning web application** that predicts whether a credit card application will be approved based on applicant information. Built using Python and Streamlit.

---

## 🚀 Features

- ✅ Trained ML model using `scikit-learn`
- 🧠 Data preprocessing and feature scaling
- 📊 Predicts **Approved** or **Denied** status
- 🌐 Clean and interactive **Streamlit Web App**
- 🔎 Includes **cross-validation** and **hyperparameter tuning**

---

## 🛠️ Tech Stack

- Python 3.10+
- pandas, numpy
- scikit-learn
- Streamlit
- pickle

---

## 📁 Project Structure

credit-card-approval/
│
├── cc_approvals.data # Original dataset
├── train_model.py # ML model training script
├── model.pkl # Trained model (pickle)
├── scaler.pkl # Preprocessing scaler
└── streamlit_app.py # Streamlit UI for predictions



---

## 🧠 How It Works

1. Dataset is cleaned, encoded, and scaled.
2. A Logistic Regression model is trained with cross-validation.
3. Final model and scaler are saved as `.pkl` files.
4. Streamlit app accepts user inputs and shows real-time predictions.

---

## ▶️ Running the Project

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/credit-card-approval.git
   cd credit-card-approval
   
Create and activate a virtual environment
python -m venv venv

venv\Scripts\activate  # Windows

source venv/bin/activate  # macOS/Linux

pip install streamlit scikit-learn pandas numpy

Train the model (optional)
python train_model.py

Run the Streamlit app
streamlit run streamlit_app.py

📈 Real-World Use Case
This project mimics a real banking scenario where machine learning automates credit approval. It demonstrates how to turn a model into a usable business tool.
