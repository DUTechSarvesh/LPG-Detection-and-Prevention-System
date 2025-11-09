# 💡 Smart LPG Leakage Detection & Safety Automation System  

## 🧩 Project Overview  
This project was built during my **B.Tech coursework (2024)** to address the **safety risks caused by LPG gas leaks** in households.  
It combines **IoT and embedded systems** using **Arduino** and **ESP32** to detect gas concentration, classify risk levels, and trigger **instant visual, sound, and digital alerts**.  
A web interface was also developed for **real-time gas monitoring and control operations**.

---

## ⚙️ System Workflow  

### 🔹 1. Gas Sensing  
- The **MQ-2 sensor** continuously monitors LPG concentration in **PPM (Parts Per Million)**.  
- Thresholds are defined (e.g., **80, 120, 150 PPM**) to categorize safety conditions.

### 🔹 2. Risk Categorization  
Depending on gas concentration, the system dynamically switches between:
- 🟢 **Normal Zone:** Safe environment  
- 🟡 **Caution Zone:** Minor leakage detected  
- 🔴 **Critical Zone:** High gas concentration detected  

### 🔹 3. Alert Mechanism  
Once the danger threshold is crossed:
- 💡 **LEDs** display status indication  
- 🔊 **Buzzer** generates an audible alert  
- 🌐 **ESP32 with Blynk** sends real-time notifications to the user  

### 🔹 4. Automated Safety Response  
- The system can automatically trigger **exhaust fans** or **valve control** to minimize further leakage.

---

## 🌍 Web Dashboard  
A dedicated website complements the hardware setup, allowing remote gas monitoring and emergency actions.  
Features include:  
- 📶 **Live Gas Data Display**  
- 🚨 **Alert Notifications**  
- ⚙️ **Device Control Panel (Fan/Regulator)**  
- ☎️ **Emergency Assistance Option**

---

## 🧰 Tools and Technologies  
- **Hardware:** Arduino, ESP32, MQ-2 Sensor, LEDs, Buzzer, Servo Motor  
- **Software:** Arduino IDE, Blynk, HTML, CSS, JavaScript  

---

## 🧪 Future Scope  
- ⚡ Integration with **smart circuit breakers (MCB)** for auto power isolation  
- 🔋 **UPS support** for continuous operation during power failures  
- 📱 Development of a **dedicated Android app** for alerts and control  

---

## 📸 Demonstration  

### 🖥️ Web Interface Preview  
<img src="https://github.com/user-attachments/assets/bd78249a-c26d-40f0-9884-e9c2944d64a4" width="800px">

### 📟 Hardware Display  
<img src="https://github.com/user-attachments/assets/28e97938-6c28-4a53-80dd-0e81d7d5ddee" width="400px">

---

## 👥 Team & Acknowledgement  
This project was completed in collaboration with my college teammates.  
My primary focus was on **web UI design**, and **system automation logic**.  

---
