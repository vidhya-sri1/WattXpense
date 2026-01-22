# WattXpense
# ⚡ Watt Xpense

**Watt Xpense** is a Smart Energy Monitoring System designed to track, analyze, and manage electricity consumption efficiently. The project provides real-time power monitoring, device-wise energy analysis, billing estimation, and insightful visual analytics to help users reduce energy wastage and optimize usage.

---

## 📌 Project Overview

Electricity consumption is increasing rapidly, and users often lack visibility into how much energy individual devices consume. **Watt Xpense** addresses this gap by offering:

* Real-time energy monitoring
* Device-wise consumption comparison
* Monthly and daily energy analytics
* Automated cost estimation
* Interactive dashboards for easy understanding

This project is suitable for **smart homes, hostels, and small commercial setups**.

---

## 🎯 Features

* 🔌 **Real-Time Power Consumption** – Live monitoring of connected devices
* 📊 **Device Consumption Comparison** – Compare energy usage across appliances
* 📈 **30-Day Energy Consumption Trend** – Visual trend analysis
* 🧾 **Monthly Energy Analytics & Share** – Monthly usage breakdown
* 💰 **Estimated Billing & Cost Analysis** – Calculate electricity expenses
* 📉 **Stacked Energy Consumption by Device** – Understand peak usage patterns
* 🖥️ **User-Friendly Dashboard** – Clean and intuitive UI

---

## 🛠️ Tech Stack

### Hardware (if applicable)

* Energy meter / current sensor (e.g., CT sensor)
* Microcontroller (ESP32 / ESP8266 / Arduino)
* Power supply modules

### Software

* **Frontend:** HTML, CSS, JavaScript (or React)
* **Backend:** Python (Django / Flask) or Node.js
* **Database:** MySQL / PostgreSQL / Firebase
* **Visualization:** Chart.js / Recharts / Power BI (optional)
* **Communication:** MQTT / HTTP / REST APIs

---

## 🧩 System Architecture

1. Sensors measure voltage and current from devices
2. Microcontroller processes and sends data to the server
3. Backend stores and processes energy data
4. Dashboard displays analytics and reports in real time

---

## 📂 Folder Structure

```
Watt-Xpense/
│── backend/
│   ├── models/
│   ├── views/
│   ├── api/
│   └── requirements.txt
│── frontend/
│   ├── public/
│   ├── components/
│   └── dashboard
│── hardware/
│   ├── circuit_diagram
│   └── sensor_code
│── docs/
│   ├── project_report.pdf
│   └── screenshots
│── README.md
```

---

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Watt-Xpense.git
cd Watt-Xpense
```

### 2. Backend Setup

```bash
pip install -r requirements.txt
python manage.py runserver
```

### 3. Frontend Setup

```bash
npm install
npm start
```

### 4. Hardware Setup

* Connect sensors to the microcontroller
* Upload firmware from `hardware/sensor_code`
* Configure Wi-Fi and server IP

---

## 📊 Dashboard Modules

* Device Status Overview
* Real-Time Power Consumption
* Monthly Energy Share
* Monthly Energy Analytics
* Device-wise Consumption Comparison
* 30-Day Consumption Trend

---

## 🔮 Future Enhancements

* AI-based energy usage prediction
* Mobile application integration
* Automated bill payment gateway
* Smart alerts for abnormal consumption
* Renewable energy (solar) integration

---

## 👩‍💻 Author

**Vidhya A**
Electronics & Communication Engineering
Energy Systems | IoT | Data Analytics Enthusiast

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use, modify, and distribute.

---

## ⭐ Acknowledgements

* Open-source IoT and data visualization communities
* Academic guidance and project mentors

---

> *“Measure today. Save tomorrow.”* ⚡
