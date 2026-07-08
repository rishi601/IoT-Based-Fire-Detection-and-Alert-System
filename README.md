# 🔥 IoT-Based Fire Detection and Alert System

An IoT-based smart fire detection system designed to detect fire and smoke in real time and immediately alert users. The project uses sensors and communication modules to enhance safety by providing early warnings and location information during fire emergencies.

---

## 📖 Overview

Fire accidents can cause significant damage to lives and property if not detected early. This project continuously monitors the environment using flame and smoke sensors. When a fire or excessive smoke is detected, the system sends an alert message along with the location using GSM and GPS modules, enabling faster emergency response.

---

## ✨ Features

- 🔥 Real-time flame detection
- 💨 Smoke detection using MQ-2 sensor
- 📍 GPS location tracking
- 📱 GSM-based SMS alerts
- ⚡ Fast emergency notification
- 🌐 IoT-enabled monitoring
- 🔄 Continuous environmental monitoring

---

## 🛠️ Hardware Components

- ESP32 Development Board
- MQ-2 Smoke Sensor
- Flame Sensor
- GSM Module (SIM800L/SIM900A)
- GPS Module (NEO-6M)
- Breadboard
- Jumper Wires
- Power Supply

---

## 💻 Software Used

- Arduino IDE
- Embedded C/C++
- ESP32 Libraries

---

## ⚙️ Working Principle

1. The MQ-2 sensor continuously monitors smoke levels.
2. The flame sensor detects the presence of fire.
3. If smoke or fire exceeds the predefined threshold:
   - The ESP32 processes the sensor data.
   - The GPS module retrieves the current location.
   - The GSM module sends an SMS alert containing the emergency message and location.
4. The system continues monitoring until the threat is resolved.

---

## 📂 Project Structure

```
IoT-Based-Fire-Detection/
│
├── Arduino_Code/
├── Circuit_Diagram/
├── Images/
├── Documentation/
├── README.md
└── LICENSE
```

---

## 🚀 Installation

1. Clone this repository.

```bash
git clone https://github.com/rishi601/iot-based-fire-detection.git
```

2. Open the Arduino code in **Arduino IDE**.

3. Install the required ESP32 board package and libraries.

4. Connect all hardware components according to the circuit diagram.

5. Upload the code to the ESP32 board.

6. Power the system and start monitoring.

---

## 📊 System Workflow

```
Smoke / Fire
      │
      ▼
Sensors Detect
      │
      ▼
ESP32 Processes Data
      │
      ├──────────────► GPS Module
      │                     │
      │                     ▼
      │               Get Current Location
      │
      ▼
GSM Module
      │
      ▼
SMS Alert Sent to User
```

---

## 🎯 Applications

- Residential Buildings
- Offices
- Warehouses
- Industries
- Schools & Colleges
- Laboratories
- Hospitals
- Commercial Buildings

---

## 📈 Future Enhancements

- Mobile application integration
- Cloud-based monitoring dashboard
- Wi-Fi notifications
- Blynk/ThingSpeak integration
- Automatic sprinkler activation
- Buzzer and LCD display
- Multiple sensor support
- Email notifications

---

## 🧠 Learning Outcomes

- IoT System Design
- Embedded Programming
- ESP32 Programming
- Sensor Integration
- GPS & GSM Communication
- Arduino IDE Development
- Real-Time Monitoring Systems

---

## 📸 Project Images

You can add screenshots or photos in the **Images** folder.

Example:

```markdown
![Circuit Diagram](Images/circuit.png)

![Prototype](Images/prototype.jpg)
```

---

## 👨‍💻 Author

**Marku Rishi Preetham**

- GitHub: https://github.com/rishi601
- LinkedIn: https://www.linkedin.com/in/markurishipreetham/

---

## 📄 License

This project is intended for educational and academic purposes.

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub. Your support is greatly appreciated!
