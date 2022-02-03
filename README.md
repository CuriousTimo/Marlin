# Marlin Firmware for Prusa Mendel i2 MK2 / MKS TinyBee / TCM2208/2209 / 1.8 Steppers

![GitHub](https://img.shields.io/github/license/marlinfirmware/marlin.svg)
![GitHub contributors](https://img.shields.io/github/contributors/marlinfirmware/marlin.svg)
![GitHub Release Date](https://img.shields.io/github/release-date/marlinfirmware/marlin.svg)
[![Build Status](https://github.com/MarlinFirmware/Marlin/workflows/CI/badge.svg?branch=bugfix-2.0.x)](https://github.com/MarlinFirmware/Marlin/actions)

<img align="right" width=175 src="buildroot/share/pixmaps/logo/marlin-250.png" />

## Specs
This firmware is configured for a Prusa Mendel i2 MK2 fitted with a MKS TinyBee and TCM2208 / TCM2209:

## Board
MKS TinyBee (https://github.com/makerbase-mks/MKS-TinyBee)

## CPU:
 - ESP32
 
### LCD Controller
 * RepRapDiscount Smart Controller

### Drivers
 * **X-axis:** BIGTREETECH TCM2209 (Standalone)
 * **Y-axis:** BIGTREETECH TCM2209 (Standalone)
 * **Z-axis 0:** BIGTREETECH TCM2208 V3.0 (Standalone)
 * **Z-axis 1:** BIGTREETECH TCM2208 V3.0 (Standalone)
 * **E0:** BIGTREETECH TCM2208 V3.0 (Standalone)

 ### Steppers
* **X-axis:** 1.8° motor
* **Y-axis:** 1.8° motor
* **Z-axis:** 1.8° motor
* **Extruder:** 1.8° motor (Original Prusa)
* **Microstepping:** 1/16

### Hotend
 * E3D Clone 12V Heater Cartridge
 * 12v 40x40x10 - hotend fan
 * 12v 4020 Blower - part cooling fan

### Probe
 * BLTouch

### Power Supply
 * 12v 

### Wiring Guide

### BOM

### Other
 * **Build Volume:** 208mm x 210mm x 123mm
 * **Firmware:** Marlin 2.0.9.3
