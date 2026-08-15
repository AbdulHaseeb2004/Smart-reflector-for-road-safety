# Smart Reflector for Road Safety

> An academic embedded-systems project designed to improve road safety using a smart, illuminated reflector system with an ESP32 controller, rechargeable battery backup, relay switching, and LED lighting.

## 📌 Project Overview

This project was developed as part of an academic engineering project to demonstrate the integration of **embedded systems, road-safety lighting, battery power, relay-based switching, and LED technology**.

The prototype is built around an **ESP32 development board** and a rechargeable **18650 Li-ion battery pack**. A relay is used for switching, while the front panel provides a physical control interface for the lighting load.

The design focuses on creating a compact, low-cost and practical smart reflector that improves the visibility of roadside objects and can continue operating from battery power when required.

## ✨ Key Features

- 🔌 ESP32-based embedded controller
- 🔋 Rechargeable 18650 Li-ion battery backup
- 💡 Dual LED lighting output
- ⚡ Relay-based electrical switching
- 🖲️ Physical ON/OFF control
- 📦 Compact custom enclosure
- 🔧 Modular wiring for easier maintenance
- 🎓 Developed as an academic engineering project

## 🧩 Hardware Components

| Component | Purpose |
|---|---|
| ESP32 Development Board | Main controller |
| 18650 Li-ion Cells | Rechargeable battery supply |
| Relay Module | Electrical load switching |
| LED Light Modules | Lighting output |
| Physical Rocker Switch | Manual control |
| Battery Holder | Secure cell mounting |
| Enclosure | Protection and assembly |
| Connecting Wires | Electrical interconnection |

> **Note:** Exact component ratings and circuit values should be verified from the physical prototype before using this project for a production or mains-powered installation.

## 🏗️ System Architecture

```text
        ┌───────────────────────┐
        │   Rechargeable        │
        │   18650 Battery Pack  │
        └───────────┬───────────┘
                    │
                    ▼
        ┌───────────────────────┐
        │       ESP32           │
        │   Control / Logic     │
        └───────┬─────────┬─────┘
                │         │
                ▼         ▼
        ┌────────────┐  ┌─────────────┐
        │ Relay      │  │ Manual      │
        │ Module     │  │ Switch      │
        └─────┬──────┘  └──────┬──────┘
              │                 │
              └────────┬────────┘
                       ▼
              ┌─────────────────┐
              │   LED Lighting  │
              │    Output       │
              └─────────────────┘
```

## 📊 Project Overview

![Smart Reflector for Road Safety — Project Overview](images/project-overview.jpg)

## 📸 Prototype

### Hardware Assembly

![Hardware Assembly](images/hardware-open.jpg)

### Front Panel

![Front Panel](images/front-panel.jpg)

### Internal Assembly

![Internal Assembly](images/internal-assembly.jpg)

## 🎥 Demonstration

A demonstration video of the working prototype is included in:

`images/demo-video.mp4`

You can also upload the video separately to the repository or attach it to the GitHub project documentation.

## 🔄 Working Principle

1. The rechargeable battery pack provides power to the embedded control circuit.
2. The ESP32 acts as the main controller.
3. The control logic determines the required lighting state.
4. The relay provides switching between the controller and the connected lighting circuit.
5. The physical switch provides direct user control.
6. The LED modules provide the final lighting output.

## 🛠️ Technologies Used

- **Embedded Systems**
- **ESP32**
- **IoT / Wireless-Ready Microcontroller Platform**
- **Relay Switching**
- **Li-ion Battery Power**
- **LED Lighting**
- **Basic Electronics & Circuit Integration**

## 📁 Repository Structure

```text
esp32-smart-emergency-light/
│
├── README.md
├── .gitignore
│
├── images/
│   ├── hardware-open.jpg
│   ├── front-panel.jpg
│   ├── internal-assembly.jpg
│   └── demo-video.mp4
│
├── src/
│   └── README.md
│
└── docs/
    └── PROJECT_NOTES.md
```

## 🚀 Getting Started

### Hardware

Before powering the prototype, verify:

- Battery polarity and cell configuration
- Battery protection/BMS arrangement
- ESP32 supply voltage
- Relay module voltage and logic compatibility
- LED module voltage/current requirements
- All exposed connections and insulation

### Firmware

Place the ESP32 firmware source code inside the `src/` directory.

The firmware should document:

- GPIO pin assignments
- Relay control logic
- Switch input logic
- Power-management logic
- Any Wi-Fi/Bluetooth functionality, if implemented

## ⚠️ Safety

This prototype contains rechargeable Li-ion cells and relay-switched electrical wiring.

**Do not connect or modify mains-voltage wiring unless you are qualified to do so.** Use appropriate insulation, fusing, protection circuitry, enclosure design, and rated components. Never charge bare 18650 cells without a suitable protection/charging circuit.

## 🎓 Academic Project

This project, **Smart Reflector for Road Safety**, was developed as part of an academic engineering curriculum to demonstrate practical knowledge of:

- Microcontrollers
- Embedded programming
- Electronics
- Power management
- Relay interfacing
- Hardware prototyping
- System integration

## 🔮 Future Improvements

- Add a proper battery-management and charging circuit
- Add battery voltage monitoring
- Add low-battery protection
- Improve enclosure and PCB layout
- Replace prototype wiring with a custom PCB
- Add remote monitoring/control if required
- Add automatic power-failure detection
- Add battery-status indication
- Improve electrical isolation and protection

## 👨‍💻 Project Status

**Status:** Completed

This repository documents the physical prototype and its implementation as an academic engineering project focused on improving visibility and safety on roads.
