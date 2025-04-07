# Tronic Spirit - Smart Automatic Fan Controller

## Overview

The project is an automatic fan control system designed to minimize electricity wastage and optimize comfort by intelligently managing fan operation in public and residential environments. Developed as part of the Engineering Design Project (EN1190) at the University of Moratuwa, this system detects human presence and ambient temperature to control fan operation automatically, while still allowing manual override.

## Features

- ✅ Automatic On/Off: Detects human presence using PIR sensors to turn the fan on or off accordingly.
- 🌡️ Smart Speed Control: Adjusts fan speed based on room temperature using a DHT11 sensor.
- 🧠 Dual Mode Operation: Switch between automatic and manual modes for flexibility.
- 🛠️ Custom PCB & Enclosure: Designed using Altium, SolidWorks, and LTSpice for simulation.
- 🔌 Microcontroller-Based: Built around the ATmega328 for reliable embedded control.

## Motivation

Public spaces often waste energy by leaving fans running when no one is present. Our goal was to create an efficient, user-friendly solution that enhances convenience while promoting sustainability.

## Architecture

- Microcontroller: ATmega328
- Sensors: DHT11 (temperature), Dual PIR sensors (presence detection)
- Modules:
  - Power Supply Module
  - Sensing Module
  - Actuation Module (Relay-based fan control)
  - User Interface Module (Buttons for manual control)
  - Main PCB for integration

## How It Works

1. Presence Detection: PIR sensors monitor for human presence.
2. Temperature Monitoring: DHT11 provides temperature data.
3. Control Logic: ATmega328 processes inputs and adjusts fan operation.
4. User Input: Buttons allow manual override of fan settings.
5. Mode Switch: Auto/Manual toggle ensures flexibility.

## Future Work

- Integration with ceiling and wall-mounted fans.
- IoT connectivity for remote control.
- Real-time energy usage analytics.







