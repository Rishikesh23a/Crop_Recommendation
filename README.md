<h1 align="center">🌾 Crop Recommendation System (Machine Learning)</h1>

<p align="center">
A Machine Learning–based Crop Recommendation App built using Python, Scikit-Learn, and Streamlit.  
This project helps farmers select the most suitable crop based on soil and environmental parameters.
</p>

---

## <h2>📌 Overview</h2>

This **Crop Recommendation System** predicts the best crop to grow using machine learning techniques.  
It uses soil features like **N, P, K**, along with **temperature, humidity, pH, and rainfall** to predict the most suitable crop.

Your repository already contains:

- ✔ Trained Random Forest model  
- ✔ Preprocessor for scaling/encoding  
- ✔ ML pipeline  
- ✔ Dataset  
- ✔ Streamlit App  
- ✔ Requirements file  

This README explains how to run, train, and understand the system.

---

## <h2>📁 Project Structure</h2>
```
Crop_Recommendation/
│
├── ml_artifacts/ # Saved ML pipeline components
│ ├── label_encoder.pkl
│ ├── scaler.pkl
│ └── other preprocessing files
│
├── best_model_RandomForest.pkl # Final trained model
├── crop_ml_pipeline.py # Model training + pipeline creation
├── final_datasetCrop_recommendationV2.xlsx # Dataset used
├── preprocessor.pkl # Full preprocessor object
├── requirements.txt # Dependencies
├── streamlit_app.py # Streamlit UI for predictions
└── .gitattributes
```
## <h2>🔍 Features</h2>

- 🌾 Predicts best crop based on soil & weather  
- 🤖 Uses **Random Forest Classifier**  
- 📊 Streamlit UI for easy use  
- 🧪 Preprocessing pipeline for consistent predictions  
- 💾 Includes complete dataset & ML artifacts  
- 🛠 Easy to deploy locally or on cloud

---

## <h2>🧠 Machine Learning Pipeline</h2>

The ML pipeline includes:

- MinMax Scaling  
- Label Encoding  
- Feature preprocessing  
- Random Forest Classifier  

Stored inside:

ml_artifacts/

preprocessor.pkl

best_model_RandomForest.pkl

<h2>⚙️ Installation</h2>
1️⃣ Clone the repository

git clone https://github.com/Rishikesh23a/Crop_Recommendation.git
cd Crop_Recommendation

2️⃣ Install required libraries

pip install -r requirements.txt

<h2>🚀 Run the Streamlit App</h2>

Launch the ML crop recommendation web app:

streamlit run streamlit_app.py


Then open:

https://crop-recommendation23.streamlit.app/


You will see a UI where you can enter:

• Temperature

• Humidity

• pH

• moisture

And the model will recommend the best crop.


<h2>📚 Dataset Information</h2>

The dataset contains:

"final_datasetCrop_recommendationV2.xlsx"

<h2>📈 Model Performance</h2>

The Random Forest model achieves:

✔ High accuracy

✔ Robust predictions

✔ Handles non-linear relationships

✔ Works well with medium-sized datasets

More details are inside your training script:

crop_ml_pipeline.py

<h2>🛠 Technologies Used</h2>

• Python

• Pandas

• NumPy

• Scikit-Learn

• Streamlit

• Joblib / Pickle

• Matplotlib / Seaborn

<h2>🔮 Future Enhancements</h2>

• Deploy on Streamlit Cloud / HuggingFace Spaces

• Add Fertilizer Recommendation System

• Add Soil Disease Detection Model

• Firebase integration for real-time IoT sensor data

• Mobile App Version 

## 📸 App Screenshots

<p align="center">
  <img src="screenshots/Screenshot 2025-10-26 000653.png" width="700">
</p>

<p align="center">
  <img src="screenshots/Screenshot 2025-10-26 005023.png" width="700">
</p>

<p align="center">
  <img src="screenshots/Screenshot 2025-10-26 010750.png" width="700">
</p>
