# 🌾 DR Crops – AI-Powered Smart Agriculture System

DR Crops is an end-to-end **AI-based smart agriculture platform** designed to assist farmers and agricultural stakeholders by combining **crop disease detection, climate-based risk analysis, market price tracking, fertilizer guidance, and chatbot assistance** into a single system.

The project supports **5 major crops** and uses both **image data and environmental parameters (temperature & humidity)** for accurate disease prediction.

---

## 🚀 Features

### 🌱 Crop Disease Detection
- Detects crop diseases from **leaf images** using deep learning.
- Supports **5 different crops**.
- Provides disease name and related insights.

### 🔀 Multi-Modal Prediction
- Combines **image features + climate data (temperature & humidity)**.
- Improves prediction reliability compared to image-only models.

### 🌦 City-Wise Disease Risk Prediction
- Predicts **potential disease risk** for a selected city.
- Uses **real-time weather data** to estimate disease occurrence probability.

### 💰 Crop Price Tracking
- Integrated **AgMarketNet** for real-time crop price information.
- Helps farmers make informed selling decisions.

### 🧪 Fertilizer Guidance
- Provides **crop- and disease-specific fertilizer recommendations**.
- Aims to improve yield and reduce crop damage.

### 🤖 Interactive AI Chatbot
- Assists users with queries related to:
  - Crop diseases
  - Fertilizers
  - Weather risks
  - Market prices

---

## 🧠 Tech Stack

- **Programming Language:** Python  
- **Deep Learning:** CNN-based models  
- **Multi-Modal ML:** Image + Climate features  
- **Backend:** Flask  
- **Frontend:** HTML, CSS, JavaScript  
- **APIs & Data Sources:**  
  - Weather API (Visual Crossing)
  - Agricultural Market Data (AgMarketNet)

---

## 📊 Datasets Used

### 🌿 Crop Disease Images
Collected and merged from multiple reliable sources:
- **Kaggle**
- **Hugging Face**
- **Mendeley Data**

These datasets were **cleaned, preprocessed, and combined** to support multi-crop disease classification.

### 🌦 Climate Data
- Sourced from **Visual Crossing Weather API**
- Parameters used:
  - Temperature
  - Humidity
  - Location (City-wise)

---

## ⚙️ System Workflow

1. User uploads a **crop leaf image**
2. Optional input of **temperature & humidity**
3. Model performs:
   - Image-based disease detection
   - Multi-modal prediction (image + climate)
4. System outputs:
   - Disease prediction
   - Risk assessment
   - Fertilizer recommendations
5. User can:
   - Check **market prices**
   - Interact with **AI chatbot**

---

## 📁 Project Structure
DR-Crops/
│── datasets/
│── models/
│── app.py
│── requirements.txt
│── static/
│── templates/
│── README.md
🎯 Use Cases

Farmers seeking early disease detection

Climate-aware crop risk assessment

Market price awareness before selling crops

Decision support for fertilizer usage

🔮 Future Enhancements

Support for more crops

Mobile application integration

Real-time satellite data integration

Multilingual chatbot support

👨‍💻 Author

Tanishq Kakkar
B.Tech CSE (AI & ML)
Bennett University

⭐ Acknowledgements

Kaggle, Hugging Face, and Mendeley for datasets

Visual Crossing for weather data

AgMarketNet for agricultural market prices
