# Hi, I'm Asma Daoud 👋

<p align="center">
  <strong>Electrical Engineering Student at ENSIT</strong><br/>
  Embedded Systems · Firmware Development · IoT · Industrial Automation · Hardware Validation
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/asma-daoud-81811a1b6">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:asma.daoud40@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/asmadaoud40-ui">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" />
  </a>
</p>

---

## 👩‍💻 About Me

I'm an Electrical Engineering student at **ENSIT (Tunisia)**, with a strong interest in embedded systems, firmware development, IoT and industrial automation.

I enjoy working at the intersection of hardware and software: developing microcontroller-based applications, integrating sensors and communication protocols, collecting data, and validating system behavior on real hardware.

Through academic projects and industrial internships, I've worked with STM32 and ESP32 platforms, distributed CAN architectures, wireless communication, industrial PLCs and automated firmware testing.

I'm particularly interested in engineering projects where embedded electronics, software, communication and system reliability come together.

🎯 **Currently looking for a 4–6 month Final-Year Internship (PFE) starting February 2027**, in embedded systems, IoT, electronics, industrial automation or hardware/software validation.

---

## 🛠️ Technical Skills

### Embedded Systems & Firmware

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat&logo=espressif&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

- STM32 bare-metal programming and peripheral configuration
- ESP32 firmware development with ESP-IDF
- GPIO, ADC, DMA, timers, PWM and interrupts
- Sensor interfacing and data acquisition
- Introduction to FreeRTOS

### Communication & IoT

![CAN](https://img.shields.io/badge/CAN_Bus-00599C?style=flat)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat&logo=mqtt&logoColor=white)
![Node-RED](https://img.shields.io/badge/Node--RED-8F0000?style=flat&logo=nodered&logoColor=white)

`UART` · `I2C` · `SPI` · `CAN` · `BLE` · `Wi-Fi` · `Modbus RTU` · `MQTT`

### Testing & Validation

- Python and pytest
- Hardware-in-the-Loop (HIL) testing
- Functional, negative and regression testing
- Hardware debugging and logic analysis
- Git and GitHub Actions CI/CD

### Industrial Automation & Engineering Tools

`Siemens S7-1200` · `TIA Portal` · `WinCC` · `EPLAN` · `AutoCAD` · `Caneco BT`

### Other Tools

`Keil MDK` · `STM32CubeIDE` · `MATLAB/Simulink` · `Node-RED` · `Git`

---

## 🔧 Selected Projects

### 🚗 Distributed Embedded System Based on CAN Bus

**STM32F407 · CAN · ESP32 · MQTT · Node-RED · Low-Power Modes**

Development of a distributed embedded architecture based on three STM32F407 microcontrollers communicating through a CAN bus.

- **Node 1:** Acquisition of three analog inputs using potentiometers and PWM-based fan control.
- **Node 2:** Temperature acquisition and RTC-based time management.
- **Central node:** Collection and coordination of data exchanged between the different nodes.
- **IoT gateway:** ESP32 forwarding data to an MQTT broker for remote monitoring through a Node-RED dashboard.
- CAN frame monitoring and communication debugging using a logic analyzer.
- Integration of low-power operating modes into the distributed architecture.

### 🧪 Automated Firmware Testing & HIL Bench

**STM32 · Arduino · Python · pytest · UART · GPIO · GitHub Actions**

Development of an automated testing environment to validate embedded firmware through hardware/software interaction.

- Development of **21 functional, negative and regression tests** using Python and pytest.
- Design of an Arduino-based HIL test bench to check physical STM32 GPIO states and compare them with UART responses.
- Automated firmware build, target flashing and test execution.
- GitHub Actions CI/CD workflow for test automation, report generation and firmware artifact publication.

### ⚡ Smart Energy Meter

**STM32F407 · PZEM-004T · Modbus RTU · ESP32 · MQTT · Node-RED**

Development of an energy monitoring system combining embedded data acquisition and IoT connectivity.

- Acquisition of voltage, current, active power and energy measurements from a PZEM-004T module using Modbus RTU.
- UART communication and register parsing on STM32F407.
- ESP32 gateway forwarding measurement data to an MQTT broker.
- Node-RED dashboard for real-time visualization, consumption monitoring and alerts.

### 🤖 IoT Bot

**STM32 · ESP32 · I2C · ADC · UART · Bluetooth · Wi-Fi · MQTT**

Development of a dual-microcontroller system combining local sensing, actuator control and wireless connectivity.

- Temperature acquisition using a DS1621 sensor over I2C.
- Three-channel analog acquisition and Bluetooth serial communication using HC-06.
- DC motor control using an L298N driver and PWM.
- STM32-to-ESP32 communication over UART.
- Publication of sensor data to ThingSpeak and a Mosquitto MQTT broker.

### 🔐 FPGA-Based Secure Node — TP-SecureNode

**Zynq-7000 · ZedBoard · VHDL · Vivado · Vitis**

Academic project focused on FPGA-based fault injection and frame corruption.

- Implementation and study of different frame corruption modes.
- Manual targeting of a selected frame, word and bit.
- Exploration of pseudo-random targeting using an LFSR and seed initialization.
- Development environment based on Vivado and Vitis.

---

## 💼 Professional Experience

### Embedded Firmware Intern — SFM Technologies
*Summer 2026 | Tunisia*

Worked on an ESP32-based IoT energy-monitoring device, focusing on wireless configuration.

- Designed and implemented a custom BLE GATT service using ESP-IDF and NimBLE.
- Added Read/Write characteristics for device identification, Wi-Fi credentials, MQTT parameters and transmission interval.
- Implemented persistent configuration storage using NVS Flash.
- Loaded saved parameters at startup and handled runtime configuration updates.
- Tested and validated the BLE interface using nRF Connect.

### Electrical Engineering Intern — La Maîtrise
*June 2025 | Tunisia*

- Prepared low-voltage electrical plans and single-line diagrams using AutoCAD.
- Performed cable and protection sizing with Caneco BT.
- Worked on electrical design requirements according to NF C 15-100.

### Final-Year Internship — Industrial Automation, CSM-GIAS
*February – June 2024 | Tunisia*

- Worked on the automation of an industrial oil transfer and storage system.
- Developed PLC control logic using Siemens S7-1200 and TIA Portal.
- Configured a TP700 HMI using WinCC.
- Worked with PROFINET remote I/O and industrial measurement equipment.
- Participated in installation testing using a water circuit.

### Electrical Maintenance Intern — ESSID Céramique
*January 2023 | Tunisia*

- Participated in electrical maintenance activities on an industrial ceramic production line.
- Gained practical exposure to industrial electrical equipment and troubleshooting.

---

## 📚 Academic Interests

- Embedded systems architecture and firmware development
- Sensor integration and signal acquisition
- Digital signal processing
- IoT communication and connected devices
- Hardware/software integration and validation
- Industrial automation and control systems
- FPGA design and digital electronics

---

## 📍 Currently

- 🎓 Electrical Engineering student at ENSIT (2024–2027)
- 🔍 Seeking a 4–6 month PFE internship starting February 2027
- 🌍 Based in Tunisia — open to opportunities in Tunisia and France
- 📚 Exploring advanced embedded systems, FreeRTOS, PCB design and data-driven applications

---

## 📬 Let's Connect

I'm open to discussing embedded systems, IoT, firmware development, electronics and engineering internship opportunities.

- 📧 **Email:** asma.daoud40@gmail.com
- 💼 **LinkedIn:** [Asma Daoud](https://www.linkedin.com/in/asma-daoud-81811a1b6)
- 💻 **GitHub:** [asmadaoud40-ui](https://github.com/asmadaoud40-ui)
