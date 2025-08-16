# ðŸ‘‹ Welcome to my GitHub

Iâ€™m Jack Walton. These are my projects for the **Deluxe Heater** system.

---

## ðŸ”¹ System Block Diagram

![Deluxe Heater Block Diagram](docs/deluxe_heater_block_diagram.png)

**Connections**
- **MainBoard (C8051F380)** â†” **DisplayDriver2 (C8051F38x)** via **UART**
- **MainBoard (C8051F380)** â†” **Thermocouple PCB** via **SPI**
- **MainBoard (C8051F380)** â†” **FrontPanel PCB** via **GPIO/Ribbon**
- **DisplayDriver2** â†” **Display** (screen interface)

---

## ðŸ”¹ Projects

### Firmware
- [**DeluxeHeater**](https://github.com/jwalton49/DeluxeHeater)  
  Main control firmware (current tag: w-DeluxeHeater-v8.40)
- [**DisplayDriver2**](https://github.com/jwalton49/DisplayDriver2)  
  Display firmware running on a C8051F38x

### Hardware (Altium Designer 20.2.7)
- [**MainBoardPCB**](https://github.com/jwalton49/MainBoardPCB) â€“ central controller PCB  
- [**FrontPanelPCB**](https://github.com/jwalton49/FrontPanelPCB) â€“ user interface PCB  
- [**ThermocouplePCB**](https://github.com/jwalton49/ThermocouplePCB) â€“ sensor interface PCB

---

## ðŸ”¹ Release Conventions
- **Firmware tags:** w-<project>-vX.Y.Z  
  Example: w-DeluxeHeater-v8.40
- **PCB tags:** pcb-<board>-R<rev>  
  Example: pcb-MainBoard-R1.2

---

## ðŸ”¹ Toolchains & CAD
- Firmware: **Keil ÂµVision 5.x**, **Simplicity Studio 5/6 (8051 support)**  
- Hardware: **Altium Designer 20.2.7**

---

âœ¨ Thanks for visiting!
