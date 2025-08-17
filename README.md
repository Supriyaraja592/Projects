# 🚦 Automated Traffic Signal Controlled in Emergency Situation

## 📌 Introduction
Traffic congestion and emergency response delays are critical challenges in modern cities.  
This project provides a **smart traffic control system** that prioritizes emergency vehicles like ambulances, fire trucks, and police cars by automatically overriding normal traffic signals.  

The solution integrates:
- **Arduino Uno** for traffic light control  
- **Android Apps (Kodular)** for transmitter and receiver  
- **Python Server** as a central controller  

📄 [View Full Project Report](AutomatedTrafficSignal_Report.pdf)

---

## 🛠️ System Overview
1. **Transmitter App (Ambulance Phone)**  
   - Sends an emergency signal when driver presses the button.  
   - Signal is transmitted via Bluetooth.  

2. **Receiver App (Traffic Signal Post)**  
   - Continuously listens for incoming signals.  
   - Measures RSSI to check if the ambulance is nearby.  
   - Sends command to Python server if valid.  

3. **Python Server (Laptop/PC)**  
   - Receives emergency data from Receiver App.  
   - Sends command `"1"` to Arduino over USB Serial.  

4. **Arduino Controller**  
   - Normally cycles traffic lights (Green → Yellow → Red).  
   - On emergency signal:  
     - Blinks white LED for 5s.  
     - Switches to green on ambulance side.  
     - Returns to normal cycle after emergency.  

---

## 📂 Project Structure

