# 🚪 RAKSH - 26 (IoT Smart Door Lock)

An innovative, secure, and remote-controllable IoT-based smart door lock system built for modern access management. This project is designed as a hackathon submission, focusing on seamless hardware-software integration, real-time access monitoring, and user convenience.

## 🌟 Key Features

- **Remote Access Control:** Lock and unlock the door from anywhere using a web or mobile dashboard.
- **Multiple Authentication Modes:** Support for RFID/NFC, PIN code, and remote app unlocking.
- **Real-Time Monitoring:** Instant notifications and logging of who accessed the door and when.
- **Automated Security Alerts:** Immediate alerts triggered on unauthorized access attempts or forced entry.
- **Fail-Safe Mechanism:** Physical override key support in case of power or network failure.

## 🛠️ Tech Stack & Components

### Hardware
- Microcontroller (e.g., ESP32 / Raspberry Pi Pico W)
- Servo / Solenoid Lock
- RFID/NFC Reader (MFRC522)
- 4x4 Keypad & OLED Display (Optional)
- Power Supply/Battery Module

### Software
- **Firmware:** C/C++ (Arduino IDE) / MicroPython
- **Backend/Database:** Node.js / Python with Firebase Realtime Database or Supabase
- **Frontend Dashboard:** React.js / Vite
- **Communication Protocol:** MQTT / WebSockets / REST API

## 🚀 Getting Started

### Prerequisites
1. Arduino IDE or PlatformIO installed.
2. Node.js and npm installed for the frontend/backend.
3. A configured database (e.g., Firebase/Supabase).

### Hardware Setup
1. Connect the servo/solenoid to the microcontroller's PWM/Relay pins.
2. Wire the RFID module via SPI.
3. Ensure stable power delivery to both the board and the lock mechanism.

### Software Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sudhanshunaik/IoT-Door-Lock.git
   cd IoT-Door-Lock
   ```

2. **Configure the Hardware:**
   - Open the firmware code in your IDE.
   - Update WiFi credentials and database connection strings/API keys.
   - Flash the code to your microcontroller.

3. **Run the Dashboard (if applicable):**
   ```bash
   cd dashboard
   npm install
   npm run dev
   ```

## 🔮 Future Enhancements

- **Biometric Integration:** Adding a capacitive fingerprint scanner.
- **Vision Agent:** Integrating a camera module for facial recognition and visitor snapshots.
- **Voice Assistant Integration:** Control the lock via Alexa or Google Assistant.
- **Battery Optimization:** Deep sleep modes for extended battery life.

## 🤝 Contributors

- **Sudhanshu Naik** - [GitHub Profile](https://github.com/Sudhanshunaik)
