# Helmet-Detection-and-Email-Alert-System
This project is a **computer vision–based safety monitoring system** that detects whether a person is wearing a helmet using **YOLO v11**.  
If a safety violation is detected (no helmet), the system automatically sends an **email alert** to the concerned authority.

The goal of this project is to demonstrate how AI can be used for **real-time safety compliance** in industrial and road environments.

---

## 🚀 Features

- Helmet detection using **YOLO v11**
- Real-time image/video-based detection
- Automated **email alert system** on safety violation
- Visual bounding boxes with confidence scores
- Scalable for CCTV and surveillance systems

---

## 🧠 Technologies Used

- Python  
- YOLO v11  
- OpenCV  
- Deep Learning  
- SMTP (Email Alerts)  
- Jupyter Notebook  

---

## 📂 Project Structure
- ├── Computer_Vision(Helmet Detection).ipynb
- ├── model/
- │ └── yolov11_weights.pt
- ├── data/
- │ └── test_images/
- ├── utils/
- │ └── email_alert.py
- └── README.md

  
---

## ⚙️ How It Works

1. Input images or video frames are passed to the **YOLO v11 model**
2. The model detects:
   - Helmet
   - No Helmet
3. If **No Helmet** is detected:
   - An **email alert** is triggered automatically
4. The alert notifies the safety authority for immediate action

---

## 📧 Email Alert System

- The system sends an automated email when a helmet violation is detected
- This makes the system **proactive**, not just informative
- Designed to reduce manual supervision and improve response time

> ⚠️ *In real-world deployment, email credentials should be stored securely using environment variables or secret managers.*

---

## 📊 Results

- Accurate helmet detection under normal lighting conditions
- Works effectively for safety monitoring scenarios
- Demonstrates real-world applicability of AI in industrial safety

---

## 🔮 Future Improvements

- Improve performance in low-light conditions
- Add cooldown logic to prevent repeated alerts
- Integrate SMS or WhatsApp alerts
- Deploy on live CCTV feeds
- Create a web-based dashboard for monitoring

---

## 💼 Use Case

- Industrial safety monitoring
- Construction site compliance
- Road and traffic surveillance
- Smart city safety solutions
