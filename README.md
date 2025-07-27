# Smart Swarm-Based Farming Assistant

## Overview  
This project is an IoT-based smart farming solution that uses a network of sensors and an ESP32 microcontroller to monitor critical farm parameters such as soil moisture, temperature, and humidity. The system integrates with a central dashboard that allows farmers to view real-time data, receive alerts, and control irrigation systems remotely. Additionally, a camera integrated with machine learning is used for plant disease detection to ensure crop health.

---

## Key Features
- **IoT Sensor Network**  
  Uses soil moisture, temperature, and humidity sensors connected to ESP32 for data collection.
  
- **Real-Time Monitoring Dashboard**  
  Displays sensor readings and provides alerts when thresholds are exceeded.

- **Remote Motor Control**  
  Farmers can switch irrigation systems on or off via the dashboard.

- **Plant Disease Detection**  
  Integrated camera with ML model for identifying plant health issues.

- **Alert System**  
  Sends email alerts if environmental parameters exceed predefined limits.

---

## Technology Stack
- **Hardware:** ESP32, DHT11, Soil Moisture Sensor, Camera Module  
- **Software:**  
  - Backend: Flask (Python)  
  - Frontend: React (Dashboard)  
  - ML Model: Plant disease detection (Python, OpenCV)  
- **Networking:** HTTP/REST API communication  

---

## System Architecture
1. Sensors collect data from the farm field.
2. ESP32 acts as the local controller and sends data to a central server.
3. The backend processes data, applies ML for disease detection, and manages alerts.
4. Dashboard (React-based UI) provides data visualization and remote controls.

---

## Use Cases
- Automated irrigation for efficient water usage.
- Early detection of plant diseases to prevent crop loss.
- Centralized farm monitoring for multiple fields.

---

## How It Works

1. ESP32 reads data from sensors and sends it to the server.
2. The server stores and processes data, triggers alerts if thresholds are crossed.
3. Farmers receive notifications and can manage irrigation via the dashboard.
4. Camera captures plant images, ML model analyzes for disease, and alerts the farmer.


---

## Images
![sensor(hw)](https://github.com/user-attachments/assets/b649818f-36aa-4fcb-aebe-5c2b3d84fa6c)
![sensor(sw)](https://github.com/user-attachments/assets/d92163bf-a110-4784-9377-99db13c2ff1d)
![sensor(ml)](https://github.com/user-attachments/assets/428d5293-df18-435a-859d-8b51335d6015)
![sensor(dash)](https://github.com/user-attachments/assets/047b0c45-04ed-4185-b510-410a5f146e66)


