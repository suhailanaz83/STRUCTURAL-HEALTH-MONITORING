# Structural Health Monitoring System

## ✅ Objective
To develop a real-time, AI-driven Structural Health Monitoring (SHM) system that detects and reports structural anomalies using simulated sensor data. The system is aimed at improving public safety and infrastructure longevity through early detection of risks such as strain, vibration, and temperature anomalies.

## 🚀 Features
- Real-time monitoring of structural parameters (strain, displacement, vibration, temperature)
- AI-based anomaly detection using Isolation Forest
- Synthetic sensor data generation for testing without physical hardware
- Data visualization using Matplotlib and Seaborn
- Smart alert logging system for detected anomalies
- Modular architecture for easy upgrades and scalability
- Secure storage and encrypted logging for system integrity

## 🛠️ Technology Used
- **Programming Language**: Python
- **Libraries**: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn
- **Algorithm**: Isolation Forest for anomaly detection
- **Version Control**: Git & GitHub
- **Platform**: Local Python environment

## ⚙️ How It Works
1. **Data Simulation**: Synthetic time-series sensor data is generated to mimic real-world structural behavior.
2. **Data Ingestion**: The system reads the data in chunks to simulate real-time streaming.
3. **Preprocessing**: Raw data is cleaned and transformed for model compatibility.
4. **Anomaly Detection**: The Isolation Forest model identifies data points that significantly differ from normal structural patterns.
5. **Visualization**: Anomalies are visualized using plots to give insights into the type and severity of structural issues.
6. **Alert Logging**: Detected anomalies are logged securely and displayed on a dashboard for engineers to act upon.

## 📊 Data Collection
The project uses **synthetically generated sensor data**, simulating realistic structural measurements:
- **Strain**
- **Displacement**
- **Vibration**
- **Temperature**

This data enables system testing and validation without physical infrastructure.

## 🎮 Controls
- Data stream simulation can be initiated and paused
- Alert thresholds can be adjusted in the configuration
- Visualizations auto-update with incoming data
- Manual re-run of model for retraining via script command

## 🤖 ML Techniques Used
- **Unsupervised Anomaly Detection** using **Isolation Forest**
- Time-series pattern recognition to identify trends and sudden changes

## 🏋️ Model Training
- The model is pre-trained on synthetic normal data
- No labeled anomaly data is required (unsupervised)
- The training includes:
  - Feature normalization
  - Isolation Forest parameter tuning
- Model retraining is modular and can be triggered when new patterns emerge

## 📥 Output Explanation
- **Graphs**: Real-time line plots showing sensor values with anomalies highlighted
- **Logs**: Anomalous events timestamped and labeled
- **Dashboard**: Summarized view of current system status and flagged risks

---

