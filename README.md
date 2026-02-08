🌟 High‑Precision Data Acquisition Module (DAQ)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![KiCad](https://img.shields.io/badge/KiCad-8.0-blue?logo=kicad&logoColor=white)
![Build](https://github.com/merouanelakdim/daq-high-precision-module/actions/workflows/build.yml/badge.svg)
![Made with Love](https://img.shields.io/badge/Made%20with-Love-red)
![GitHub stars](https://img.shields.io/github/stars/merouanelakdim/daq-high-precision-module?style=social)
![Repo Size](https://img.shields.io/github/repo-size/merouanelakdim/daq-high-precision-module)

A compact and robust 4‑channel data acquisition module designed with a strong focus on signal integrity, low noise, and clean analog/digital separation.
Built around an STM32 microcontroller, an analog multiplexer, and carefully tuned RC filtering, this board is engineered for reliable and accurate measurements.

🚀 Features
4 multiplexed analog input channels

STM32 microcontroller for fast sampling and processing

Optimized RC filter (R4/C9) for ADC input stabilization

Clean analog/digital domain separation

UART interface for communication

SWD interface for programming and debugging

2‑layer PCB designed with KiCad

Low‑noise power architecture with ferrite bead isolation

🧩 Hardware Architecture
Analog Front-End

4 input channels

Multiplexer for channel selection

RC low‑pass filter to stabilize ADC readings

Digital Core

STM32 MCU

SPI communication

UART interface

SWD programming header

Power Section

5V input

3.3V regulation

Analog/digital power separation

Decoupling and filtering for noise reduction

📁 Repository Structure
Code
📦 daq-high-precision-module
 ┣ 📂 hardware/        → KiCad project files (schematic + PCB)
 ┗ 📜 README.md        → You are here
🖼️ PCB Preview
<img width="1051" height="818" alt="image" src="https://github.com/user-attachments/assets/621cab7f-011f-48dc-b1ac-a3a1b488cf70" />

🎯 Project Goals
Build a compact and reliable DAQ module

Ensure clean analog signal acquisition

Apply professional PCB design practices

Optimize routing for low noise and stability

Provide a reusable hardware platform for future projects

🛠️ Tools & Technologies
KiCad 8 for schematic and PCB design

STM32 ecosystem

LTspice for analog simulation

Git & GitHub for version control

👤 Author
Merouane Lakdim  
Embedded Electronics Engineer — Paris, France
Passionate about hardware design, signal integrity, and embedded systems.

📄 License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
