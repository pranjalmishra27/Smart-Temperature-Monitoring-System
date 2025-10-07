# 🌡️ Smart Temperature Monitoring System

A simple **Arduino-based embedded system** that monitors temperature and humidity using a **DHT11 sensor** and controls a **fan automatically** when the temperature crosses a defined threshold. The system displays real-time readings on a 16x2 LCD.

---

## 🔧 Components Used
- Arduino Uno  
- DHT11 Temperature & Humidity Sensor  
- 16x2 LCD Display  
- Relay Module (for fan control)  
- Jumper Wires and Breadboard  

---

## ⚙️ Working Principle
1. The DHT11 sensor continuously measures temperature and humidity.  
2. Readings are displayed on the LCD screen.  
3. When temperature exceeds a preset threshold (default 30°C), the fan turns ON.  
4. The fan automatically turns OFF when temperature falls below the threshold.  

---

## 🧠 Technologies & Concepts
- Embedded C Programming  
- Arduino I/O Control  
- Sensor Interfacing (DHT11)  
- LCD Display Communication  
- Basic Automation Logic  

---

## 🪄 Circuit Connections
| Component | Arduino Pin |
|------------|--------------|
| DHT11 Signal | D2 |
| LCD RS | D12 |
| LCD E | D11 |
| LCD D4–D7 | D5, D4, D3, D6 |
| Fan Relay | D8 |

---

## 📸 Output
- LCD displays real-time temperature and humidity.  
- Fan automatically toggles ON/OFF based on temperature.

---

## 🚀 How to Run
1. Connect components as per the circuit.  
2. Open `Smart_Temperature_Monitoring_System.ino` in the Arduino IDE.  
3. Select **Arduino Uno** and correct **COM port**.  
4. Upload the code and observe the readings on LCD.  
## 🧾 License
This project is open-source and free to use for learning and educational purposes.
