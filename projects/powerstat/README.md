# Powerstat – Energy Monitoring & Control System

## Overview  
Powerstat is a multi-channel energy monitoring and control system designed for industrial and agricultural environments. The system measures voltage, current, power quality, and supports remote control via mobile app integration.

## Technical Highlights  
- Schematic & PCB designed in KiCad / Altium  
- Embedded firmware for STM32 with RS485, NB-IoT communication  
- Mobile UI built with Flutter, real-time data and control  
- Power management circuitry for 24V → 12V / 5V / 8V rails  

## Challenges & Solutions  
- Noise filtering in analog front-end for accurate measurements  
- Multi-layer routing constraints in tight form factor  
- Ensuring robust connectivity over NB-IoT under field conditions  

## Deployment  
- Deployed units tested in pump stations and agricultural fields  
- Field photos and UI screenshots available in `mobile_ui/` and `field_photos/`

## File Structure  
- `schematics/` – PDF / source files  
- `pcb_layouts/` – Gerber / board visuals  
- `firmware/` – Embedded C / source code  
- `mobile_ui/` – UI screenshots, layout files  
- `field_photos/` – Device in real environment  