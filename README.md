# 🏥 Medical Insurance Purchase Prediction App  

![Streamlit](https://img.shields.io/badge/Built%20with-Streamlit-red?logo=streamlit)  
![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)  
![License](https://img.shields.io/badge/License-MIT-green)  
![Status](https://img.shields.io/badge/Status-Deployed-brightgreen)  

This is a **Streamlit web application** that predicts whether a customer is likely **to purchase or not purchase medical insurance** based on their **Age, Estimated Salary, and Gender**.  

The model is powered by a **Random Forest Classifier** trained on sample insurance data.  

---

## 🚀 Live Demo  
👉 [Click here to use the app](https://medicalinsurance1.streamlit.app/)  

---

## 📸 Screenshots  
| Home Page | Prediction Example |  
|-----------|-------------------|  
| ![Home Screenshot](https://via.placeholder.com/500x300.png?text=App+Home+Page) | ![Prediction Screenshot](https://via.placeholder.com/500x300.png?text=Prediction+Result) |  

---

## 📌 Features  
- ✅ Interactive web interface built with **Streamlit**  
- ✅ Input fields: **Age, Estimated Salary, Gender**  
- ✅ Predicts customer intent: *“to purchase”* / *“not to purchase”*  
- ✅ Model powered by **Random Forest (scikit-learn)**  
- ✅ Deployed online via **Streamlit Cloud**  

---

## 🛠️ Tech Stack  
- **Python 3.9+**  
- **Streamlit**  
- **Scikit-learn**  
- **NumPy**  
- **Pandas**  

---

## 📂 Project Structure  
Medical-insurance/
│── app.py # Main Streamlit app
│── rfmodel.pkl # Trained Random Forest model
│── requirements.txt # Dependencies
│── README.md # Project documentation


---

## ⚙️ Installation & Usage Locally  

1. Clone the repo:  
   ```bash
   git clone https://github.com/SUNPAUL97/Medical-insurance-.git
   cd Medical-insurance-
2. Install dependencies:
   pip install -r requirements.txt
3. Run the app:
   streamlit run app.py

   🔍 Future Improvements

Add more predictive features (e.g., health records, lifestyle data)

Enhance UI with custom CSS/Bootstrap for a modern look

Store user inputs in a database (PostgreSQL / Firebase)

Deploy with Docker for scalability

🙌 Author

👤 Paul



GitHub: @SUNPAUL97
⭐ If you like this project, give it a star to support the work! ⭐
