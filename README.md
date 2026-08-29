# Micromouse Hardware Design (KiCad)

Hardware schematics and design files for an autonomous Micromouse robot based on the **ESP32-S3 SuperMini**.

---

> ⚠️ **IMPORTANT NOTICE:**  
> The physical hardware of this robot is built entirely on a **Prototype Board (Perfboard/Dot board)** using manual point-to-point soldering.  
> The included **PCB layout file (`.kicad_pcb`) is provided for reference only** (visualizing routing logic and footprint planning) and **has NOT been tested or validated for direct PCB manufacturing**. Please refer to the **Schematic (`.kicad_sch`)** for wiring connections when assembling on a proto-board or designing your custom PCB.

---

## 🧩 Bill of Materials (Key Components)

| Component | Model / Description | Function |
| :--- | :--- | :--- |
| **MCU** | ESP32-S3 SuperMini | Main controller (Logic, Navigation, PID) |
| **I/O Expander** | PCF8574 (I2C) | GPIO expansion for sensor control / indicators |
| **Motors** | GA12-N20 Micro Gearmotors | Differential drive with dual-channel quadrature encoders |
| **Motor Driver** | TB6612FNG Dual H-Bridge | Motor direction and PWM speed control |
| **Distance Sensors** | VL6180 (ToF / Range Finder) | Wall detection & precise distance sensing (I2C) |
| **Power Management**| Step-Down Buck Converter (to 3.3V) | High-efficiency voltage regulation for MCU and logic |
| **Circuit Base** | Prototype Board (Perfboard FR4) | Point-to-point hand-soldered foundation |

---

## 📁 Repository Structure

```text
.
├── hardware/
│   ├── micromouse.kicad_pro     # KiCad Project File
│   ├── micromouse.kicad_sch     # Full Circuit Schematic (Primary reference)
│   ├── micromouse.kicad_pcb     # Reference PCB Layout (Do NOT fabricate directly)
│   └── micromouse.kicad_prl     # Project Local Settings
└── README.md
```
## View it 
https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2Fdancejjjjj%2FMicromouse-Board-Design%2Ftree%2Fmain%2Fhardware
