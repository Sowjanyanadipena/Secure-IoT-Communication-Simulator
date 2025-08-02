# 🚀 Secure IoT Communication Simulator
This project simulates secure IoT device communication using the MQTT protocol over a public broker. It mimics real-time temperature and humidity sensor data sent from a virtual IoT device to an MQTT server. The project is designed to help understand IoT messaging patterns and how publish-subscribe architectures work.
## 🔧 Features
- Simulates sensor data (temperature & humidity)
- Uses the MQTT protocol for publish/subscribe messaging
- Sends data to `test.mosquitto.org` (public MQTT broker)
- Visualizes live data flow in the console
- Can be extended to add encryption, data plotting, or multi-client simulation
## 📦 Technologies Used
- Python 3
- paho-mqtt
- Threading
- Google Colab / Jupyter Notebook
## ▶️ How to Run
1. Open the `.ipynb` file in Google Colab or Jupyter.
2. Install the required package:
   ```bash
   !pip install paho-mqtt
