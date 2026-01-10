# 🚗 Vehicle Damage Predictor (Car)

A deep learning–powered web application that predicts **vehicle (car) damage** from uploaded images.  
The project demonstrates an **end-to-end DL inference pipeline**, combining model serving with a web interface.

---

## 📌 Project Overview

This project allows users to upload an image of a car and receive a **damage prediction** using a trained deep learning model.

The system is built with:
- **FastAPI** for model inference (backend API)
- **Streamlit** for the user-facing web app
- A trained **computer vision model** for damage prediction

The focus is on **practical ML deployment**, not just model training.

---

## 🧠 How It Works

1. User uploads a car image through the Streamlit app  
2. Image is sent to a FastAPI endpoint  
3. Backend processes the image and runs model inference  
4. Prediction result is returned and displayed to the user  

---
## 🖼️ Application Screenshots

Streamlit Web App
<!-- Screenshot 1 -->

<!-- Screenshot 2 -->
---

## 🏗️ Project Structure

```text
damage-prediction/
│
├── fast-api-server/
│   ├── server.py            # FastAPI app
│   ├── model_helper.py      # Model loading & prediction logic
│
├── streamlit-app/
│   ├── app.py               # Streamlit frontend
│   ├── model/               # Trained model files
│   ├── requirements.txt
│
├── training/
│   └── ...                  # Model training notebooks/scripts
│
└── README.md

