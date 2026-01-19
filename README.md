# ESP32-C3 Dev Board (KiCad) ⚡

A custom **ESP32-C3 development board** designed in **KiCad**, built for compact embedded prototyping with
**USB-C input, LiPo charging, stable 3.3V regulation**, and expansion headers for sensors/modules.

✅ Focus: **Embedded Hardware • PCB Design • Power + IO Integration**

---

## ✅ Key Features
- **ESP32-C3-WROOM module**
- **USB-C power input**
- **Single-cell LiPo charging circuit**
- **3.3V regulation** for stable MCU + peripherals
- **Boot / Reset circuit** for easy programming
- **GPIO breakout headers** for expansion
- Sensor/module support (example: **BME280**, mic amplifier, photo sensor)

---

## 📷 PCB Preview
### Top Layer
![Top](docs/pcb-renders/top.png)

### Bottom Layer
![Bottom](docs/pcb-renders/bottom.png)

---

## 📂 Repository Structure
```txt
esp-devboard-prateek/
│── README.md
│── LICENSE
│
├── hardware/
│   └── kicad/               # KiCad project files (.kicad_pro/.sch/.pcb)
│
├── docs/
│   ├── schematic.pdf        # Schematic export
│   └── pcb-renders/         # Top/Bottom/3D screenshots
│
└── fabrication/             # (optional) Gerbers, drill, BOM, PnP outputs
