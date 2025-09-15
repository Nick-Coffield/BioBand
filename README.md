# BioBand

BioBand is a wrist-worn IoT prototype that monitors vital signs and environmental data in real-time. This project integrates multiple sensors to capture:

- Heart rate (BPM) and blood oxygen (SpO₂) via MAX30102  
- Body temperature via TMP117  
- Motion and activity via MPU-6050 accelerometer/gyroscope  
- Ambient temperature, humidity, and air quality via BME680  

Data is transmitted to a mobile app using Bluetooth Low Energy (BLE), enabling live monitoring and logging. The device is powered by a compact LiPo battery and housed in a wearable enclosure suitable for the wrist.

## Features
- Compact, wrist-worn form factor  
- Multi-sensor integration for biometrics and environmental monitoring  
- BLE streaming to smartphone applications  
- Optional OLED display for real-time feedback  
- Expandable for cloud data integration  

## Tech Stack
- **Microcontroller:** ESP32 (Wi-Fi & BLE)  
- **Sensors:** MAX30102, TMP117, MPU6050, BME680  
- **Communication:** Bluetooth Low Energy (BLE)  
- **Power:** LiPo battery with TP4056 charging module  
- **Display:** SSD1306 OLED (optional)
