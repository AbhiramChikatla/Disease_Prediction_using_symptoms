# 🩺 Disease Prediction Using Symptoms

This project is a **Streamlit-based web application** that predicts potential diseases based on user-provided symptoms using a machine learning model.

![Streamlit App Preview](https://github.com/AbhiramChikatla/Disease_Prediction_using_symptoms/assets/preview-image.png) <!-- Optional: Replace or remove -->

---

## 🚀 Live Demo

👉 [Click here to try the app](https://predict-my-illness.streamlit.app)

---

## 📌 Features

- 🧠 Predicts disease using symptoms
- 📊 Trained using Decision Tree Classifier
- 📋 Simple and intuitive user interface with Streamlit
- 🛠️ Lightweight and fast to use

---

## 🔍 How It Works

1. Users input their symptoms through a dropdown.
2. The system encodes symptoms as binary vectors.
3. A trained machine learning model (`DecisionTreeClassifier`) predicts the disease.
4. Result is shown instantly on the web interface.

---

## 🧰 Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python, Pandas, NumPy
- **ML Model**: Scikit-learn (Decision Tree)
- **Deployment**: Streamlit Cloud
- **Serialization**: Joblib

---

## 📁 Project Structure
├── app.py # Main Streamlit application
├── saved_model/
│ └── decision_tree.joblib # Pre-trained model
├── data/
│ └── dataset.csv # Symptom-disease dataset
├── environment.yml # Conda environment for deployment
├── requirements.txt # Python packages list (pip)
└── README.md # You're reading this!



---

## 🛠️ Setup Instructions

### ▶️ Run Locally

```bash
# Clone the repo
git clone https://github.com/AbhiramChikatla/Disease_Prediction_using_symptoms.git
cd Disease_Prediction_using_symptoms

# Create virtual environment
conda env create -f environment.yml
conda activate MachineLearning

# OR using pip
# pip install -r requirements.txt

# Run Streamlit app
streamlit run app.py

🙌 Acknowledgements
Dataset inspired by multiple open-source medical symptom repositories

Thanks to Streamlit for the easy deployment platform

📬 Contact
Abhiram Chikatla
🔗 GitHub | ✉️ abhiram.chikatla@email.com (Replace with your real contact)


---

You can now save this as `README.md` in your project root and push it to GitHub:

```bash
git add README.md
git commit -m "Add project README"
git push origin main
