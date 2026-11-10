# Rover Parker

An autonomous, gesture-controlled exploration rover. This repo is an index —
each component lives in its own repository for independent development.

---

## 🔧 Components

| Component | Description | Stack | Repo |
|---|---|---|---|
| 🧠 **App** | Flutter control app (Manual + Autonomous modes) | Flutter, Dart | [rover-app](https://github.com/dangnguyen06-ee/Autonomous_Rover_App) |
| 🔌 **Firmware** | Onboard control & sensor fusion | ESP32-S3, C++ | [rover-firmware](https://dangnguyen06-ee/Autonomous_Rover_Firmware) |
| ⚡ **PCB** | Main control board, motor driver, sensor breakout | KiCad | [rover-pcb](https://github.com/dangnguyen06-ee/Autonomous_Rover_PCB) |
| 🧊 **3D Model** | Chassis, sensor mounts, enclosure | Fusion 360, STL | [rover-3d](https://github.com/willbeupdated) |
| 👁️ **Computer Vision** | Gesture recognition pipeline | Python, MediaPipe | [rover-cv](https://github.com/dangnguyen06-ee/Autonomous_Rover_CV) |

---

## ✨ Features

- 🎮 **Manual mode** — drive over Wi-Fi from the mobile app
- 🤖 **Autonomous mode** — follow hand gestures via onboard camera
- 📷 **Live camera stream** — see what the rover sees
- 🧭 **Obstacle detection** — ToF + ultrasonic + IMU fusion

---

## 🧱 Hardware

| Part | Model |
|---|---|
| MCU | ESP32-S3 |
| ToF Sensor | VL53L5X |
| Ultrasonic | HC-SR04 |
| IMU | BNO085 |
| Camera | Onboard, CameraX |
| Power | 3000 mAh Li-ion |

---

## 👥 Team

| Name | Role |
|---|---|
| [@dangnguyen06-ee](https://github.com/dangnguyen06-ee) | blah blah blah |
| [@teammate](https://github.com/teammate) | blah blah blah |
| [@teammate2](https://github.com/teammate2) | blah blah blah |

---

## 📜 License

MIT — see individual repos for details.
