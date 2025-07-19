# Environment_gas_detection-_app
# 🔍 Air Quality Monitoring & Alert System (Arduino + Android - Java)

This project is a smart IoT-based Android application developed using **Java** that monitors the concentration of harmful gases in the air using sensors connected to an **Arduino**. The app communicates with the Arduino via **Bluetooth** and sends **SMS alerts** with the user's current **GPS location** when gas levels exceed a safe threshold.

---

## 📱 Features

- 📡 Real-time gas monitoring using MQ-series sensors (e.g., MQ-2, MQ-7)
- 🔗 Bluetooth communication with Arduino via HC-05/HC-06 module
- 🚨 Auto SMS alerts to a predefined contact when gas index exceeds safety limits
- 📍 GPS integration to send real-time location with alert
- 📊 Simple and user-friendly interface
- 🔒 Emergency contact setup within the app

---

## 🛠️ Tech Stack

| Component      | Technology               |
|----------------|---------------------------|
| Mobile App     | Android (Java)           |
| Hardware       | Arduino UNO              |
| Communication  | Bluetooth (HC-05/06)     |
| Gas Detection  | MQ-series Gas Sensors    |
| APIs Used      | Android SMS Manager, Google Location API |

---

## 🔗 How It Works

1. **Arduino Setup:**
   - MQ sensors detect gas concentration in the environment.
   - Data is sent via the HC-05 Bluetooth module.

2. **Android App:**
   - Receives data from Arduino over Bluetooth.
   - Displays real-time gas index.
   - Sends an SMS with the gas index and current GPS location if the level exceeds the danger threshold.

---

## 📦 Installation & Setup

### 🔌 Arduino Side
- Connect MQ sensors to Arduino UNO.
- Connect Bluetooth module (HC-05) to Arduino.
- Upload Arduino sketch for reading sensor values and sending them over Bluetooth.

### 📲 Android Side
- Clone this repo and open in **Android Studio**.
- Pair your phone with HC-05 Bluetooth.
- Grant permissions for location and SMS.
- Run the app on your Android device.

---

## 📸 Screenshots
<img width="372" height="647" alt="image" src="https://github.com/user-attachments/assets/59891a07-db7c-4178-96fe-f99184b6f906" />




---

## 🚀 Use Cases

- Indoor air pollution detection
- Industrial safety systems
- Smart city monitoring
- Fire or gas leak alerts

---

## 🤝 Contributions

Feel free to open issues or submit pull requests if you'd like to contribute.

---

## 📜 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Developed By

**Akash Kumar Singh**  
Java Developer | IoT Enthusiast | Full Stack Engineer  
📧 kmrakash350@gmail.com  
📱 +91-9508849717  

