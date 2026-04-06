# 🤖 Smart Bin — Automatic Dustbin with IR Sensor

**Created by MoxyzJeffrey aka Jeff C137 | AI Robotics Innovation Hub**

A hands-free automatic dustbin that opens its lid when you 
wave your hand near it. Built with an ESP32, FC-51 IR sensor 
and 28BYJ-48 stepper motor.

---

## 📺 Watch the Full Build Video
👉 [Jeff C137 YouTube — Smart Bin](https://www.youtube.com/@JEF-C137)

---

## ⚙️ Components Used
- ESP32 Dev Board (38-pin)
- FC-51 Infrared Proximity Sensor
- 28BYJ-48 Stepper Motor (5V)
- ULN2003 Motor Driver Board
- Active Buzzer (5V)
- Breadboard + Jumper Wires

---

## 📌 Pin Reference
| Component      | Pin        | ESP32 GPIO |
|----------------|------------|------------|
| IR Sensor      | OUT        | GPIO 33    |
| Buzzer         | Positive   | GPIO 2     |
| ULN2003        | IN1        | GPIO 14    |
| ULN2003        | IN2        | GPIO 26    |
| ULN2003        | IN3        | GPIO 27    |
| ULN2003        | IN4        | GPIO 25    |

---

## 🚀 How to Use
1. Wire components as per pin reference above
2. Open smart_bin.ino in Arduino IDE
3. Select Board: ESP32 Dev Module
4. Upload and power on — lid will home to closed position
5. Wave hand near IR sensor to open!

---

## 📄 Full Documentation
See SmartBin_GitHub_Documentation.docx in this repo

---

## 🔗 Connect
- YouTube: Jeff C137
- Organisation: AI Robotics Innovation Hub

⭐ Star this repo if it helped you!
