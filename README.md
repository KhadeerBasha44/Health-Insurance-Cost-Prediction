# **Health Insurance Cost Prediction using Machine Learning**  

## **📌 Project Overview**  
This project aims to predict health insurance costs using **Machine Learning** techniques. By analyzing factors like age, BMI, smoking habits, and region, the model provides accurate cost estimates, helping individuals and insurers make informed decisions.  

### **🔹 Key Features**  
✅ **Multiple ML Algorithms Compared** (Logistic Regression, SVM, Random Forest, Gradient Boosting)  
✅ **Best Model: Gradient Boosting (87.8% Accuracy)**  
✅ **Interactive Web App** (Built with Streamlit)  
✅ **Desktop GUI** (Built with Tkinter)  
✅ **Data Preprocessing & Feature Engineering**  

---

## **📂 Project Structure**  
```
Health-Insurance-Cost-Prediction/  
│── data/  
│   └── insurance.csv                # Dataset (from Kaggle)  
│── models/  
│   └── gradient_boosting_model.pkl  # Trained model (Pickle)  
│── notebooks/  
│   └── EDA_and_Model_Training.ipynb # Jupyter Notebook for EDA & training  
│── app/  
│   ├── streamlit_app.py             # Streamlit Web App  
│   └── tkinter_gui.py               # Desktop GUI  
│── requirements.txt                 # Python dependencies  
└── README.md  
```  

---

## **🛠️ Installation & Setup**  

### **1. Clone the Repository**  
```bash
git clone https://github.com/yourusername/Health-Insurance-Cost-Prediction.git
cd Health-Insurance-Cost-Prediction
```

### **2. Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **3. Run the Streamlit Web App**  
```bash
streamlit run app/streamlit_app.py
```

### **4. Run the Tkinter Desktop GUI**  
```bash
python app/tkinter_gui.py
```

---

## **📊 Dataset Description**  
The dataset (`insurance.csv`) contains **1,338 records** with **7 features**:  

| Feature       | Description                          | Data Type  |
|--------------|-------------------------------------|-----------|
| `age`        | Age of the insured person           | Numeric   |
| `sex`        | Gender (Male/Female)                | Categorical |
| `bmi`        | Body Mass Index                     | Numeric   |
| `children`   | Number of dependents                | Numeric   |
| `smoker`     | Smoking status (Yes/No)             | Categorical |
| `region`     | Residential region (4 categories)   | Categorical |
| `charges`    | Insurance cost (Target Variable)    | Numeric   |

🔗 **Dataset Source:** [Kaggle - Medical Cost Personal Datasets](https://www.kaggle.com/datasets/mirichoi0218/insurance)  

---

## **🤖 Machine Learning Models Compared**  
| Model               | Accuracy (R² Score) |
|---------------------|-------------------|
| **Gradient Boosting**  | **0.878** (Best) |
| Random Forest       | 0.866            |
| Logistic Regression | 0.783            |
| SVM                 | -0.072 (Poor fit) |

**Final Model:** `GradientBoostingRegressor`  

---

## **🖥️ Applications**  

### **1. Streamlit Web App**  
🔹 **User-friendly interface** for predicting insurance costs  
🔹 **Real-time results** based on input parameters  

📌 **How to Use:**  
1. Adjust sliders for **Age, BMI, Children, etc.**  
2. Select **Smoker (Yes/No)** and **Region**  
3. Click **"Predict"** to get the estimated cost  

![Streamlit App Demo](https://via.placeholder.com/600x400?text=Streamlit+App+Demo)  

### **2. Tkinter Desktop GUI**  
🔹 **Offline prediction tool**  
🔹 Simple form-based input  

![Tkinter GUI Demo](https://via.placeholder.com/600x400?text=Tkinter+GUI+Demo)  

---

## **📌 Key Findings & Insights**  
✔ **Smokers pay significantly higher premiums** (2-3x more than non-smokers)  
✔ **BMI and Age strongly influence insurance costs**  
✔ **Gradient Boosting outperforms other models** in accuracy  

---

## **📜 References**  
1. Kaggle Dataset: [Medical Cost Personal Datasets](https://www.kaggle.com/datasets/mirichoi0218/insurance)  
2. Scikit-learn Documentation: [Gradient Boosting](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html)  
3. Streamlit: [Official Docs](https://docs.streamlit.io/)  

---

## **📧 Contact**  
👤 **Khadeer Basha K**  
📧 khadeershaik2906@gmail.com
🔗 LinkedIn: (https://linkedin.com/in/khadeer-basha-k-0a3b4b278/)  

---

## **🎯 Future Improvements**  
🔹 **Deploy the model on AWS/GCP** for cloud-based predictions  
🔹 **Add user authentication** for personalized cost tracking  
🔹 **Improve UI/UX** with better visualizations  

---

**🚀 Happy Predicting!** 🚀  

---

