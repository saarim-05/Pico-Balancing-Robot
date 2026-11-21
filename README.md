# WobbleBot

A two-wheeled self-balancing robot built with a Raspberry Pi Pico W, MPU6050 IMU, and metal-gear encoder motors. Designed in Siemens NX and programmed in MicroPython.

## Authors
Amina Raiymbayeva & Saarim Munir (METU ME 2nd year)

## Overview
- **Balance Control:** Uses an MPU6050 accelerometer/gyroscope and a PID feedback loop on the Pico W to stay upright and recover from disturbances.
- **Wireless Driving:** Accepts manual drive and steering commands over Wi-Fi from a laptop.
- **Display:** Front-mounted OLED screen showing real-time status expressions.

## Folder Structure
- `cad/` – Siemens NX part and assembly files
- `code/` – MicroPython firmware and laptop control scripts
- `docs/` – Parts list, wiring diagrams, and development roadmap
