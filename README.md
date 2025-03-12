# Customer Churn Prediction using ANN (Artificial Neural Network)

## 📖 Project Overview  
Customer churn prediction helps businesses identify customers likely to leave. This project implements an **Artificial Neural Network (ANN) classifier** using TensorFlow/Keras to predict churn based on customer behavior.

🖥️ **Live Demo**: [Customer Churn Prediction](https://customerchurnpredictionma.streamlit.app/)
---

## ⚙️ Model Architecture  
The ANN classifier consists of the following layers:

1️⃣ **Input Layer**: Takes customer data as input  
2️⃣ **Hidden Layers**:  
   - Dense layers with **ReLU activation**  
   - Dropout layers for regularization  
3️⃣ **Output Layer**:  
   - **Sigmoid activation** for binary classification (Churn: Yes/No)  

**Loss Function:** `binary_crossentropy`  
**Optimizer:** `Adam`  
**Evaluation Metrics:** `accuracy`

---