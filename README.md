# 🍄 Automated Mushroom Grow Box

An Arduino-based environmental control system designed to automatically regulate temperature and humidity for mushroom cultivation.

Although the original source code has unfortunately been lost, the complete hardware design, enclosure, electronics and user interface are documented here as part of my engineering portfolio.

---

# Project Overview

This project was built entirely from scratch to create a fully automated growing environment.

The system continuously monitors temperature and humidity using environmental sensors and automatically controls:

- Heating
- Cooling
- Humidification

through relay-controlled devices.

The enclosure also includes a user interface allowing multiple configurable presets and manual testing of every subsystem.

---

# Finished Project

![Finished](Images/IMG-20241222-WA0003.jpg)

The completed grow box with custom wooden enclosure, aluminium frame, sliding lid and integrated control panel.

---

# Features

- Automatic temperature regulation
- Automatic humidity regulation
- Multiple saved presets
- Manual testing mode
- LCD menu interface
- Matrix keypad navigation
- Real-time sensor monitoring
- Relay controlled outputs
- Custom enclosure
- 3D printed components
- Arduino based controller

---

# Control Panel

![Front Panel](Images/IMG-20241222-WA0002.jpg)

The front panel contains:

- LCD Display
- 4x4 Matrix Keypad
- USB programming access
- Main power switch

The menu system allows configuring presets without reconnecting the Arduino.

---

# User Interface

## Main Menu

![Main Menu](Images/main_menu.jpg)

The firmware contains several operating modes:

- Automatic operation
- Choose preset
- Edit presets
- Tester mode

---

## Automatic Mode

![Automatic](Images/autonomus_menu.jpg)

Displays:

- Current temperature
- Current humidity
- Heating status
- Cooling status
- Humidifier status

---

## Preset Selection

![Choose Preset](Images/chose_preset_menu.jpg)

Multiple temperature presets can be stored for different mushroom species.

---

## Editing Presets

![Edit Presets](Images/write_min_max_hum.jpg)

Each preset stores:

- Maximum temperature
- Minimum temperature
- Humidity target

---

## Stored Presets

![Preset List](Images/set_preset_menu.jpg)

Several environmental profiles can be saved and loaded directly from the keypad.

---

## Tester Mode

![Tester](Images/tester_mode.jpg)

Every output can be tested independently without running automatic control.

This made hardware debugging significantly easier.

---

# Electronics

## Arduino Controller

![Arduino](Images/arduinouno_screw_shield.jpg)

The controller is built around an Arduino Uno.

To improve reliability, a screw terminal shield was used for every external connection.

---

## Custom Screw Shield Cover

![Shield Cover](Images/arduinouno_screw_shield_cover_connected.jpg)

I designed and 3D printed a protective cover to keep all wiring secure while still allowing easy maintenance.

---

# Internal Construction

## Front Access

![Front Open](Images/finished_open_front.jpg)

The front panel provides access to the control electronics.

---

## Rear Cooling System

![Rear](Images/finished_open_back.jpg)

The rear contains the cooling assembly with multiple high airflow fans.

---

## Internal Wiring

![Open](Images/finished_open_left.jpg)

All wiring was routed manually and connected through screw terminals for easy servicing.

---

# Cooling Assembly

![Cooling](Images/uncovered_back.jpg)

Three high airflow fans provide active cooling of the enclosure when temperatures exceed the configured maximum.

---

# LCD Development

Early firmware versions displayed:

![Prototype](Images/unfinished_screen.jpg)

before the complete menu system was implemented.

---

# Technologies Used

## Hardware

- Arduino Uno
- Relay Modules
- LCD 20x4 Display
- 4x4 Matrix Keypad
- Environmental Sensor
- Multiple Cooling Fans
- Heating Element
- Humidifier
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

This project taught me:

- Embedded software architecture
- State machine design
- Menu systems
- Sensor integration
- Relay control
- Environmental automation
- Hardware debugging
- Electrical wiring
- Mechanical enclosure design
- 3D printing for functional parts

---

# Future Improvements

If I rebuild this project I would like to add:

- ESP32 with Wi-Fi
- Remote monitoring
- Web dashboard
- Data logging
- Automatic graphs
- Mobile notifications
- Better cable management

---

# Note

Unfortunately the original Arduino source code has been lost after a hardware failure.

This repository documents the hardware design and development process as part of my engineering portfolio.