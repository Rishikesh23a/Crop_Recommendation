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
