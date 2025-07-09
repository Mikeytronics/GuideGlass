# 👓 GuideGlass

**Guide Glass** is a smart wearable designed to assist visually impaired users by providing spatial awareness through auditory feedback. It integrates distance sensors, motion tracking, and bone conduction audio to enhance safety and navigation in real-time.

---

## 📦 Features

- 🔊 **Bone Conduction Audio**: Delivers real-time feedback without blocking ambient sound.
- 🧠 **ESP32 Microcontroller**: Handles sensor processing and audio control.
- 📏 **Time-of-Flight (ToF) Sensors**: Detect nearby obstacles with precision.
- 🌀 **IMU (LSM6DS3)**: Tracks head tilt to adjust feedback based on user movement.
- 💡 **LED Indicators**: Visual alerts for additional safety (e.g., night use).
- 🔋 **Battery Powered & Wearable**: Lightweight and rechargeable design.
- 📡 **Bluetooth Ready** *(planned)*: Future updates will enable wireless configuration and data logging.
- 🧠 **AI-Ready** *(planned)*: Intended for future integration with gesture recognition or language translation.

### 🧰 Requirements

- 🔬 3D Printer with filament
- 💻 EasyEDA or KiCad for PCB edits
- 🪛 Soldering tools for through-hole assembly
- ♨️ Hot plate/hot air gun and solder paste (or order PCB assembly service)

#### 🔩 Hardware

- McMaster-Carr M2-.4x05 screws
- ESP32-WROOM-32E module
- VL53L1X ToF sensors (x2)
- LSM6DS3 IMU
- MAX98357 I2S Audio Amplifier (x2)
- Bone Conduction Speakers
- Arduino IDE or PlatformIO
- Li-Po Battery & Smart Charger
- 28(for power) and 30-36(for signals) AWG wire
- Additional LEDs, diodes, resistors and capacitors (0805 SMD), and other components*


*Most are included on the PCB gerber files

Test circuit example found here:
https://www.youtube.com/watch?v=D4u7eDeQFEw 
