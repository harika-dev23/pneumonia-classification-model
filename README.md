# Pneumonia Detection Web Application Using Deep Learning

## Overview
This project is an **end-to-end Deep Learning–based Pneumonia Detection Web Application** that analyzes medical images and predicts whether a patient shows signs of **Pneumonia**.

The application integrates a **trained deep learning model**, a **Flask backend**, and a **responsive web interface**, providing real-time predictions through a browser-based UI. The project is structured for **local execution and cloud deployment**.

## Problem Statement
Early detection of pneumonia is critical for timely medical intervention. Manual diagnosis from medical images can be time-consuming and subjective.  
This project automates pneumonia detection using a **trained deep learning model** and makes it accessible through a web application.

## System Architecture
```
User Uploads Medical Image
↓
Web Interface (HTML / CSS / JS)
↓
Flask Backend
↓
Deep Learning Model (.h5)
↓
Prediction: Pneumonia / Normal
```

## Tech Stack
- **Backend:** Python, Flask  
- **Deep Learning:** TensorFlow, Keras  
- **Frontend:** HTML, CSS, JavaScript, Bootstrap  
- **Model Format:** HDF5 (`.h5`)  
- **Deployment:** Procfile (cloud-ready)

## Project Structure

```
pneumonia-classification-model/
├── app.py # Flask application
├── trained_model.h5 # Trained deep learning model
├── requirements.txt # Python dependencies
├── Procfile # Deployment configuration
├── templates/
│ ├── index.html # Main prediction UI
│ └── base.html # Common layout (navbar, styling)
├── static/
│ ├── css/
│ │ └── main.css
│ └── js/
│ └── main.js
└── README.md # Documentation
```

## Deep Learning Model
- Pre-trained neural network stored in `.h5` format
- Loaded during application startup
- Performs inference on uploaded medical images
- Outputs prediction results in real time

## Web Application Features
- Upload medical images via browser
- Real-time pneumonia prediction
- Clean, responsive UI using Bootstrap
- Backend–frontend integration using Flask templates
- Ready for cloud deployment

## How to Run the Project Locally
1. Install Dependencies
pip install -r requirements.txt
2. Run the Application
python app.py
3. Access the Application
http://localhost:

