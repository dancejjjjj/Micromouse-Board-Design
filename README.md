# Micromouse Hardware Design (KiCad)

Hardware schematics and design files for an autonomous Micromouse robot based on the **ESP32-S3 SuperMini**.

---

> ⚠️ **IMPORTANT NOTICE:**  
> The physical hardware of this robot is built entirely on a **Prototype Board (Perfboard/Dot board)** using manual point-to-point soldering.  
> The included **PCB layout file (`.kicad_pcb`) is provided for reference only** (visualizing routing logic and footprint planning) and **has NOT been tested or validated for direct PCB manufacturing**. Please refer to the **Schematic (`.kicad_sch`)** for wiring connections when assembling on a proto-board or designing your custom PCB.

---

## 🧩 Bill of Materials (Key Components)

![Image](https://github.com/dancejjjjj/Micromouse-Board-Design/blob/main/assets/BOM.png)

Google sheet link here:
https://docs.google.com/spreadsheets/d/1piouLKvGbAHOj3b3Lox_jSpBq9OYytLLw8UId9fDQRM/edit?usp=sharing

---

## 📁 Repository Structure

```text
.
├── pcb/
│   ├── micromouse.kicad_pro     # KiCad Project File
│   ├── micromouse.kicad_sch     # Full Circuit Schematic (Primary reference)
│   └── micromouse.kicad_pcb     # Reference PCB Layout (Do NOT fabricate directly)
|   
├── BOM.csv
└── README.md
```
## View it 
https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2Fdancejjjjj%2FMicromouse-Board-Design%2Ftree%2Fmain%2Fpcb
