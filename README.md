# Welcome to my GitHub

---

## System Block Diagram

![Block Diagram](docs/deluxe_heater_block_diagram.png)

# Deluxe Heater Project

## Connections

- **MainBoard (C8051F380)** ↔ **DisplayDriver2 (C8051F38x)** via UART  
- **MainBoard (C8051F380)** ↔ **ThermocouplePCB** via SPI  
- **MainBoard (C8051F380)** ↔ **FrontPanelPCB** via GPIO / Ribbon cable  
- **DisplayDriver2** ↔ **Display** (screen interface)


---

## Projects

### Firmware
- [DeluxeHeater](https://github.com/jwalton49/DeluxeHeater)  
  Main control firmware (current tag: `fw-DeluxeHeater-v8.40`)

- [DisplayDriver2](https://github.com/jwalton49/DisplayDriver2)  
  Display firmware running on a C8051F38x (current tag: `fw-DisplayDriver2-v1.0`)

### Hardware (Altium Designer 20.2.7)
- [MainBoardPCB](https://github.com/jwalton49/MainBoardPCB)  
  Central controller PCB (current tag: `pcb-MainBoard-R061525`)

- [ThermocouplePCB](https://github.com/jwalton49/ThermocouplePCB)  
  Sensor interface PCB (current tag: `pcb-Thermocouple-R07272025`)

- [FrontPanelPCB](https://github.com/jwalton49/FrontPanelPCB)  
  User interface PCB (current tag: `pcb-FrontPanel-R122893`)

---

## Release Conventions

- **Firmware tags**: `fw--ProjectName-vX.Y[.Z]`  
  Example: `fw-DeluxeHeater-v8.40`

- **PCB tags**: `pcb--BoardName-RYYYYMMDD` or `pcb--BoardName-Rn.m`  
  Example: `pcb-MainBoard-R061525`

---

##  Toolchains & CAD
- Firmware: **Keil µVision 5.x**, **Simplicity Studio 5/6 (8051 support)**  
- Hardware: **Altium Designer 20.2.7**

---

¨ Thanks for visiting!
