# HexPulse DIY RF Lab

A homemade DIY RF testing setup powered by ESP32, HexPulse firmware, and HexMind AI.

This project demonstrates how to build a simple low-cost RF testing lab using:
- ESP32 development board
- DIY copper-wire antenna
- Homemade Wi-Fi signal extender
- HexPulse firmware
- HexMind AI integration

Designed for:
- RF experimentation
- Wi-Fi signal analysis
- Bluetooth signal testing
- Educational electronics
- DIY cybersecurity learning

---

# Preview

![Setup](media/setup.jpg)

---

# Features

- DIY homemade antenna
- Portable ESP32 setup
- Wi-Fi signal scanning
- Bluetooth testing
- Lightweight hardware
- Expandable RF experiments
- Open-source workflow
- AI-assisted testing using HexMind

---

# Project Architecture

```text
DIY Antenna
     ↓
ESP32 + HexPulse Firmware
     ↓
Wi-Fi / Bluetooth Testing
     ↓
HexMind AI Analysis
```

---

# Hardware Used

| Component | Purpose |
|---|---|
| ESP32 Dev Board | Main RF controller |
| Copper Wire | Homemade antenna |
| Breadboard | Connections |
| Jumper Wires | Wiring |
| USB Cable | Power |
| Electrical Tape | Insulation |
| Optional Router Antenna | Extended testing |

---

# DIY Homemade Signal Extender

This project uses a very simple handmade antenna system built using copper wire.

## Materials Required

- Copper wire
- Pen or small plastic tube
- Tape
- ESP32 board
- USB power source

---

# Build Guide

## Step 1 — Create Coil

Wrap copper wire around a pen:
- 6 to 8 turns
- Keep spacing equal
- Leave wire ends exposed

## Step 2 — Shape Antenna

Stretch one side slightly upward.

This helps improve signal reception.

## Step 3 — Connect to ESP32

Attach the copper wire carefully to the antenna section.

## Step 4 — Secure Setup

Use tape to stabilize the wire.

## Step 5 — Power On

Connect ESP32 via USB.

---

# Firmware

## HexPulse Firmware

GitHub Repository:

[github.com](https://reference-url-citation.invalid/0)

---

# HexMind AI

HexMind is used for AI-assisted cybersecurity workflows and RF analysis. 1

## Official Links

- [hexmind.space](https://reference-url-citation.invalid/2)
- [github.com](https://reference-url-citation.invalid/3)

---

# Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/HexPulse-DIY-RF-Lab.git
cd HexPulse-DIY-RF-Lab
```

---

# Flash Firmware

## Install ESPTool

```bash
pip install esptool
```

## Flash

```bash
esptool.py --chip esp32 write_flash 0x0000 firmware.bin
```

---

# Usage

1. Power on ESP32
2. Launch HexPulse firmware
3. Connect with HexMind
4. Begin signal testing
5. Monitor Wi-Fi and Bluetooth activity

---

# Folder Structure

```text
HexPulse-DIY-RF-Lab/
│
├── firmware/
├── hardware/
├── docs/
├── media/
├── scripts/
├── README.md
└── LICENSE
```

---

# Example Use Cases

- DIY RF learning
- Educational Wi-Fi experiments
- Bluetooth signal testing
- ESP32 experimentation
- Portable RF lab builds

---

# Legal Notice

This project is strictly for:
- Educational purposes
- Authorized testing
- Research environments

Do NOT use against networks or devices without permission.

The author is not responsible for misuse.

---

# Future Improvements

- Better antenna designs
- OLED signal monitor
- Battery-powered portable version
- Advanced RF visualization
- Web dashboard integration

---

# Credits

Built by Arjun T M (CyberKallan)

Powered by:
- ESP32
- HexPulse
- HexMind AI

---

# Disclaimer

This repository does NOT promote unauthorized access or illegal activities.

All testing must remain ethical and legal.

---

# Star The Repo

If you like the project:
- Star the repository
- Fork the project
- Share your DIY upgrades

Happy building 🚀
