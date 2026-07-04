# 🍄 Automated Mushroom Grow Box

An Arduino-based environmental control system designed to automatically regulate temperature and humidity for mushroom cultivation using active thermoelectric cooling, electric heating and a fully configurable LCD interface.

Although the original source code has unfortunately been lost, the complete hardware design, enclosure, electronics and user interface are documented here as part of my engineering portfolio.

---

# Project Overview

This project was designed and built entirely from scratch to create a fully automated growing environment for mushroom cultivation.

The system continuously monitors temperature and humidity and automatically controls the environment by activating:

- Heating
- Active thermoelectric cooling
- Humidification

using relay-controlled devices.

A custom LCD menu system allows the user to configure environmental presets, manually test every subsystem and monitor the current operating conditions without connecting the Arduino to a computer.

---

# Finished Project

![Finished Grow Box](images/IMG-20241222-WA0003.jpg)

The completed grow box featuring a custom wooden enclosure, aluminium frame, sliding insulated lid, LCD interface and integrated environmental controller.

---

# Removable Lid Design

![Finished Grow Box](images/IMG-20241222-WA0001.jpg)

One design goal was to make the enclosure easy to clean and maintain.

The lid is completely removable and the LED lighting together with the temperature/humidity sensor are connected through magnetic electrical connectors.

The three visible cables automatically connect when the lid is installed, allowing it to be removed in seconds without disconnecting any wiring.

---

# Features

- Automatic temperature regulation
- Automatic humidity regulation
- Three Peltier thermoelectric cooling modules
- Electric heating system
- Multiple high airflow cooling fans
- Multiple configurable presets
- Manual hardware testing mode
- LCD menu interface
- Matrix keypad navigation
- Real-time sensor monitoring
- Relay controlled outputs
- Custom wooden enclosure
- 3D printed components
- Arduino based controller

---

# Control Panel

![Control Panel](images/controll_pad.jpg)

The front panel contains:

- 20x4 LCD display
- 4x4 matrix keypad
- USB programming access
- Main power switch

The complete system can be configured directly from the control panel without reconnecting the Arduino to a computer.

---

# User Interface

## Main Menu

![Main Menu](images/main_menu.jpg)

The firmware is organized into several operating modes:

- Automatic Mode
- Choose Preset
- Edit Presets
- Tester Mode

---

## Automatic Mode

![Automatic Mode](images/autonomus_menu.jpg)

During operation the display continuously shows:

- Current temperature
- Current humidity
- Heating status
- Cooling status
- Humidifier status

allowing the system to be monitored in real time.

---

## Preset Selection

![Preset Selection](images/chose_preset_menu.jpg)

Different environmental profiles can be stored and selected depending on the mushroom species being cultivated.

---

## Editing Presets

![Preset Editor](images/write_min_max_hum.jpg)

Each preset allows configuration of:

- Minimum temperature
- Maximum temperature
- Target humidity

The settings are stored directly from the keypad interface.

---

## Stored Presets

![Stored Presets](images/set_preset_menu.jpg)

Multiple preset profiles can be saved and loaded directly from the LCD menu.

---

## Tester Mode

![Tester Mode](images/tester_mode_menu.jpg)

Every output can be activated independently.

This mode was extremely useful while debugging the electronics, relays and sensors during development.

---

# Electronics

## Arduino Controller

![Arduino Controller](images/arduinouno_screw_shield.jpg)

The controller is built around an Arduino Uno equipped with a screw terminal shield to simplify wiring and improve reliability.

---

## Custom Electronics Cover

![Electronics Cover](images/arduinouno_screw_shield_cover_connected.jpg)

To protect the wiring I designed and 3D printed a custom cover for the screw terminal shield.

The cover keeps every connection secure while still allowing quick access for maintenance.

---

# Internal Construction

## Front Access

![Front Access](images/finished_open_front.jpg)

The front compartment provides access to the electronics, relay modules and power distribution.

The enclosure was designed so individual components can be serviced without completely disassembling the system.

---

## Rear Cooling Assembly

![Rear Cooling](images/finished_open_back.jpg)

The rear compartment houses the active cooling system including heatsinks, Peltier modules and cooling fans.

---

## Internal Wiring

![Internal Wiring](images/finished_open_left.jpg)

All electrical connections are routed through screw terminals to simplify maintenance and replacement of individual components.

---

# Cooling System

![Cooling System](images/uncovered_back.jpg)

Unlike traditional grow boxes that rely only on ventilation, this project uses **three Peltier (thermoelectric) modules** to actively cool the enclosure.

The Arduino activates the Peltiers whenever the temperature exceeds the configured limit.

Large heatsinks together with multiple high-airflow fans remove heat from the hot side of the modules while circulating cooled air throughout the enclosure.

This allows the system to both heat and actively cool the internal environment depending on the current conditions.

---

# Early Development

![Prototype Interface](images/unfinished_screen.jpg)

Early firmware versions focused on testing the LCD interface before the complete menu system and configuration pages were implemented.

---

# Technologies Used

## Hardware

- Arduino Uno
- Screw Terminal Shield
- LCD 20x4 Display
- 4x4 Matrix Keypad
- Temperature & Humidity Sensor
- 3x Peltier Thermoelectric Modules
- Multiple Cooling Fans
- Heating Element
- Relay Modules
- Custom Power Supply

## Software

- Arduino IDE
- C++
- Embedded Programming

## Manufacturing

- 3D Printing
- CAD Design
- Woodworking
- Electrical Wiring

---

# Lessons Learned

This project provided practical experience in:

- Embedded software architecture
- State machine design
- LCD menu systems
- Sensor integration
- Relay control
- Environmental automation
- Thermal management
- Electrical wiring
- Mechanical enclosure design
- 3D printing functional components
- System integration and debugging

---

# Future Improvements

If I rebuild this project I would like to add:

- ESP32 controller
- Wi-Fi connectivity
- Remote monitoring
- Web dashboard
- Historical temperature and humidity logging
- Mobile notifications
- PID temperature control
- Automatic data visualization
- Improved cable management

---

# Note

Unfortunately the original Arduino source code has been lost after a hardware failure.

This repository preserves the hardware design, user interface, mechanical construction and engineering decisions behind the project as part of my personal engineering portfolio.

