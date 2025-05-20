# Design-of-a-Smart-Home-Control-System-Using-IoT-Technology

This is a project for applicating IoT in a Smart Home.

## 🚀 Feature
- Read temperature and huminity with DHT11 sensor
- Read fire (digital signal), smoke(analog signal), rain(analog signal) sensors and send data to web dashboard, then procceed to control buzzle and servos
- Connect Wifi and send data via MQTT (AdaFruit IO)
- Can control window and door (this is servos) via web server or app
- Using RFID open a main door for my house
  
## 🛠️ Hardward Components
- ESP32 DevKit V1
- DHT11 sensor
- RFID
- Servos
- Fire sensor
- Smoke sensor
- Rain sensor
- Buzzle
- Adapter (5V-3A/2A)
  
## 🧰 Software Components
- Arduino IDE

## 🔧 Cài đặt

### 1. Clone repository
```bash
git clone https://github.com/yourusername/smart-sensor-node.git
cd smart-sensor-node
