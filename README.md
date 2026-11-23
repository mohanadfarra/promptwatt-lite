# ⚡ PromptWATT-Lite — Smart DC Power Monitoring & Control

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Embedded C](https://img.shields.io/badge/Embedded%20C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![AI](https://img.shields.io/badge/AI-tool%20calling-8b5cf6?style=flat-square)

> Embedded Systems course project · SMU MedTech · Sep – Dec 2025

A **two-channel DC power monitoring and control system** that measures voltage, current and power in
real time, shows them on a web dashboard, and lets an **AI assistant** help manage loads safely.

<p align="center">
  <img src="media/prototype.jpg" alt="PromptWATT-Lite prototype" width="520">
</p>

## 🧩 How it works

| Layer | Details |
|---|---|
| **Sensing** | Analog voltage/current sensing circuits on two DC channels |
| **Firmware** | STM32 handles real-time acquisition and load switching |
| **Connectivity** | ESP32 Wi-Fi module streams data to the dashboard |
| **Supervision** | Web dashboard for live readings and control |
| **AI control** | An LLM with a strict system prompt and a small set of tools can read measurements and switch loads within safety rules. Several models were benchmarked for accuracy, speed and resource use. |

## 🎥 Demo

[▶️ Watch the demo video](media/demo.mp4)

## 📄 Documents

- [Full project report (32 pages)](docs/PromptWATT-Lite_Report.pdf) — design, circuits, AI architecture, LLM benchmark, diagrams and code

## 👥 Team

Ibrahim Fourati · Louay Arfa · Camille Badji · **Mohanad Alfarra**
