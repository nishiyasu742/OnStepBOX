# OnStepBOX

OnStepBOX is a compact, integrated controller box that combines an OnStep-compatible Smart Hand Controller (SHC) and the main OnStep controller into a single unit.  
This project is based on the **OnStep MaxESP3 hardware design** and uses the **OnStep firmware (GPLv3 licensed)**.  

---

## Overview

- **Purpose**: Simplify telescope control by merging two devices (main OnStep controller + SHC) into one.  
- **Base design**: Derived from the [OnStep MaxESP3](https://onstep.groups.io/g/main/wiki/MaxESP3) hardware.  
- **Firmware**: Fully compatible with OnStep firmware (licensed under GPLv3).  
- **Use case**: Ideal for amateur astronomers who want a reliable, compact, and user-friendly OnStep system without carrying multiple devices.  

---

## Features

- Integrated SHC and OnStep controller in a single enclosure  
- Based on the proven **OnStep MaxESP3 circuit design**  
- Compatible with the official OnStep firmware (GPLv3)  
- USB-PD powered stepper motor driver with TMC2209 support  
- Compact build using an off-the-shelf plastic enclosure (machined, not 3D-printed)  
- Designed for DIY assembly with widely available components  

---

## Photos

> Replace with actual photos of the assembled unit, inside and outside.

- Image captured using a Takahashi EM200 mount.  
  ![１](https://github.com/user-attachments/assets/b6eef8e2-6a49-451e-a25b-f3ea39513ce8)


- OnStepBOX's appearance  
  ![２](https://github.com/user-attachments/assets/d4c9ff88-3c86-483d-a861-04df58b4baf9)

- The bottom surface of OnStepBOX  
 ![３](https://github.com/user-attachments/assets/0d02b4d1-f0de-44f6-b6c1-69fcf6772284)


- Inside the OnStepBOX  
  ![４](https://github.com/user-attachments/assets/f67b535e-504f-4364-8aed-e7f253490f6c)


---

## Schematic & Pin Mapping

This project follows the **OnStep MaxESP3** pin mapping for firmware configuration.  
Be sure to select the correct board definition in OnStep when compiling.  

- Example schematic (simplified):  
 ![OnStepBOX回路図](https://github.com/user-attachments/assets/bd2e13ab-23ee-4c81-b1a7-56473de34f30)


> ⚠️ Please confirm wiring carefully. Incorrect wiring may damage your board or motors.

---

## Required Components

- ESP32 development board (ESP-WROOM-32 recommended)  
- Stepper motor drivers (e.g., TMC2209)  
- USB-PD trigger module  
- Standard OnStep-compatible connectors and cables  
- Off-the-shelf plastic enclosure (e.g., Takachi LC135-H-N-W)  
- Miscellaneous components (buttons, display, etc.)  

---

## Assembly Instructions

1. **Prepare the enclosure**  
   - Machine openings for connectors, display, and buttons.  
2. **Mount the ESP32 and motor drivers**  
   - Use standoffs or direct PCB mounting as appropriate.  
3. **Wire according to schematic**  
   - Follow the **MaxESP3 pin map** for OnStep firmware.  
4. **Install OnStep firmware**  
   - Download the latest OnStep firmware.  
   - Configure pins according to MaxESP3.  
   - Flash firmware to ESP32.  
5. **Final checks**  
   - Verify motor movement.  
   - Test SHC interface.  
   - Confirm alignment and control with telescope mount.  

---

## License

This project is distributed under the **GNU General Public License v3 (GPLv3)**.  
Since it is derived from **OnStep hardware and firmware**, it must remain open source.  

- A full copy of the GPLv3 license text is included in the [LICENSE](LICENSE) file.  

---

## Acknowledgments

- Original [OnStep project](https://onstep.groups.io/g/main) by **Howard Dutton** and contributors  
- OnStep MaxESP3 hardware design (the base for this project)  
- Open-source astronomy community for valuable feedback and improvements  

---

— NEWEVI
