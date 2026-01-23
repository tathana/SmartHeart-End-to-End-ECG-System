# SmartHeart Care – End-to-End AI Health Monitoring System

SmartHeart Care is a prototype preventive healthcare system for 
continuous ECG monitoring and AI-based heart condition classification.

This repository serves as the **system overview and architecture** of SmartHeart.
The actual implementations are separated into the following repositories:

### 🔹 Core Capstone System
- **SmartHeart_Care**  
  Main capstone implementation including system logic, backend design, and integration plan  
  👉 https://github.com/tathana/SmartHeart_Care

### 🔹 Baseline & Model Experiments
- **smartheart-ecg-analysis-test**  
  Baseline ECG model training, experiments, and evaluation  
  👉 https://github.com/tathana/smartheart-ecg-analysis-test

### 🔹 Course Demo / Prototype
- **ecg-streamlit-app**  
  Streamlit application for ECG classification (CNN image-based, course project)  
  👉 https://github.com/tathana/ecg-streamlit-app
  
## System Overview
The system is designed using a layered architecture:
- Edge Layer: Wearable ECG device + Flutter mobile app
- Cloud Layer: Backend API, Time-series database, AI analysis
- Dashboard Layer: Caregiver and Doctor dashboards

## Architecture
📄 Detailed system architecture and design documentation:
- [System Architecture](System requirement and Architecture.pdf)

## Related Repositories
This repository acts as a **project overview**.  
Implementation details are separated into the following repositories:

- **Mobile & Device**
  - Flutter Mobile App (private / in progress)

- **AI & Data Analysis**
  - smartheart-ecg-analysis-test  
    Baseline ECG model training and experimentation

- **Deployment / Visualization**
  - ecg-streamlit-app  
    Streamlit app for ECG classification (CNN-based, academic use)

## Disclaimer
This system is a prototype for preventive health monitoring and
is not intended for medical diagnosis.
