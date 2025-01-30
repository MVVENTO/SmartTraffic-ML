# 🚦 AI-Powered Traffic Management for a Safer, Smarter NYC 🌍

## **📌 Project Overview**

Traffic congestion significantly contributes to **carbon emissions** and urban pollution. This project leverages **machine learning** to optimize **traffic flow**, enhance **public safety**, reduce **congestion**, and **lower emissions** by analyzing real-time traffic data, predicting congestion patterns, and implementing AI-driven traffic signal optimization.

## **🎯 Objectives**

✔️ **Predict** traffic congestion using historical and real-time data to forecast congestion patterns.\
✔️ **Optimize** traffic light timing with Reinforcement Learning (RL) to dynamically adjust traffic signal timing based on real-time conditions.\
✔️ **Suggest eco-friendly routes** : Provide drivers with route options that minimize emissions and fuel consumption.\
✔️ **Integrate** carbon footprint analytics for city planners : Develop tools for city planners to analyze the environmental impact of traffic management strategies.

## **🛠️ Tech Stack**

| Component          | Technology                  |
| ------------------ | --------------------------- |
| Programming        | Python, TensorFlow, PyTorch |
| Data Processing    | Pandas, NumPy, Scikit-Learn |
| Traffic Simulation | Tom Tom                     |
| API Development    | FastAPI           |
| Visualization      | Streamlit / React + D3.js   |
| Deployment         | Google Cloud / AWS          |

## **📡 Data Sources**

- **Cityscapes Dataset** (Urban scene understanding & real-world traffic scenarios)
- **NYC Open Data** (Real-time traffic data)
- **Google Maps API** (Route & congestion data)
- **NOAA Weather API** (Weather impact on traffic)
- **EPA Air Quality API** (Carbon emissions data)

## **🧠 Why Use the Cityscapes Dataset Instead of Satellite Images?**

While satellite imagery provides a **macro view** of traffic conditions, it lacks the fine-grained details necessary for understanding **road-level dynamics**. The **Cityscapes dataset** is a **better fit** because:

| Feature                      | Cityscapes Dataset                                          | Satellite Images                                     |
| ---------------------------- | ----------------------------------------------------------- | ---------------------------------------------------- |
| Road-Level Detail            | ✅ Yes (lane markings, pedestrian crossings, traffic lights) | ❌ No (low-resolution view)                           |
| Vehicle Detection            | ✅ Yes (cars, buses, cyclists, pedestrians)                  | ❌ Limited (difficult to differentiate vehicle types) |
| Traffic Light Analysis       | ✅ Yes (identifies traffic signals & interactions)           | ❌ No (not clearly visible)                           |
| Real-World Application       | ✅ Urban traffic patterns, congestion hotspots               | ❌ Large-scale observation but lacks fine details     |
| Machine Learning Suitability | ✅ Labeled for segmentation & detection                      | ❌ Requires heavy preprocessing                       |

By using **Cityscapes**, we can train machine learning models to **recognize real-world traffic elements**, making AI-powered predictions **more accurate and actionable**.

## **🧐 Machine Learning Models**

| Task                          | Model                                   |
| ----------------------------- | --------------------------------------- |
| Traffic Flow Prediction       | LSTM / Time Series Forecasting          |
| Smart Traffic Signal Control  | Reinforcement Learning (Deep Q-Network) |
| Eco-Friendly Route Suggestion | Graph Neural Networks (GNN)             |

## **🚀 Project Workflow**

1⃣ **Data Collection** – Gather traffic & emission data.\
2⃣ **Data Preprocessing** – Clean & analyze datasets.\
3⃣ **ML Model Development** – Train traffic prediction & RL models.\
4⃣ **Simulation** – Validate using SUMO traffic simulation.\
5⃣ **API & Dashboard** – Build a frontend to visualize insights.\
6⃣ **Deployment** – Deploy on Google Cloud / AWS.

## **🗓 Timeline**

| Phase      | Duration                        | Task |
| ---------- | ------------------------------- | ---- |
| Week 1-3   | Data Collection & Preprocessing |      |
| Week 4-7   | ML Model Training               |      |
| Week 8-10  | Traffic Simulation & Testing    |      |
| Week 11-12 | API & Dashboard Development     |      |
| Week 13-14 | Optimization & Deployment       |      |

## **🌍 Real-World Impact**

✔️ Reduces **carbon footprint** by optimizing traffic flow.\
✔️ Helps **city planners** make data-driven decisions.\
✔️ Supports **emergency response** by predicting road congestion.

## **📂 How to Run the Project**

1⃣ Clone the repository

```bash
git clone https://github.com/mvento/SmartTraffic-ML.git
cd SmartTraffic-ML
```

2⃣ Install dependencies

```bash
pip install -r requirements.txt
```

3⃣ Run the application

```bash
python main.py
```

This project brings **cutting-edge AI** to traffic management, leveraging **urban-level insights** for a smarter and **more sustainable NYC**! 🌍🚗

