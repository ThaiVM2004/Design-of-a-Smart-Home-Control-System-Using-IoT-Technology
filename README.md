# Design-of-a-Smart-Home-Control-System-Using-IoT-Technology

Một dự án IoT thu thập dữ liệu môi trường và gửi về server qua MQTT.

## 🚀 Tính năng
- Đọc nhiệt độ, độ ẩm từ DHT22
- Kết nối WiFi và gửi dữ liệu qua MQTT
- Cấu hình dễ dàng qua file `.env` hoặc serial

## 🛠️ Yêu cầu phần cứng
- ESP32 DevKit V1
- Cảm biến DHT22
- Nguồn 5V/2A
- (Tuỳ chọn) OLED SSD1306 để hiển thị

## 🧰 Yêu cầu phần mềm
- PlatformIO (hoặc Arduino IDE)
- MQTT broker (ví dụ: Mosquitto)

## 🔧 Cài đặt

### 1. Clone repository
```bash
git clone https://github.com/yourusername/smart-sensor-node.git
cd smart-sensor-node
