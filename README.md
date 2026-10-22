# Trespass Trap – Smart Security System

## Overview

**Trespass Trap** is an electronic security monitoring and control system that integrates **C# .NET, Arduino microcontrollers, sensors, and electronic actuators**.

The project was originally designed and developed by **Haeytham Al Malak in 2022** as a Computer Engineering Technology capstone project at Seneca Polytechnic.

The original implementation used **USB Serial Communication** between the C# .NET control application and Arduino hardware. Wireless communication using **Bluetooth (HC-05)** was explored and tested during a later development phase as part of the planned expansion toward remotely located substations.

## Features

- Developed a **C# .NET desktop application** as the central monitoring and control interface for security personnel.
- Established **USB Serial Communication** between the main application and Arduino-based hardware.
- Integrated motion sensors to detect unauthorized activity and trigger alarm responses.
- Implemented electronic controls for lighting, a siren, and a door-locking mechanism.
- Enabled the central application to receive status information and issue control commands.
- Integrated IP camera monitoring over a local network.
- Provided alarm management functions, including reset and temporary alarm suspension.
- Designed the system architecture with future expansion to multiple security substations in mind.

## Communication and Development Phases

### Phase 1 – Original Capstone Implementation (2022)

The original system used **USB Serial Communication** to exchange commands and status information between the C# .NET desktop application and Arduino microcontroller hardware.

This implementation demonstrated the integration of software, sensors, electronic outputs, and security monitoring functions.

### Phase 2 – Wireless Communication Development

Following the original capstone, Bluetooth communication using **HC-05 modules** was explored and tested as part of the project's planned wireless development.

The objective was to reduce dependence on wired connections and investigate how remotely located security substations could communicate with a central monitoring station.

This later experimental development was separate from the original capstone implementation.

**Note:** Supporting multiple independently managed substations was a longer-term design objective, not a completed feature of the original 2022 application.

## Technologies Used

- **C# .NET:** Desktop monitoring application, user interface, and device control.
- **Arduino / Embedded C:** Sensor monitoring and control of connected electronic devices.
- **USB Serial Communication:** Communication method used in the original implementation.
- **Bluetooth (HC-05):** Later wireless communication development and testing.
- **Motion Sensors:** Detection of activity in monitored areas.
- **Relays and Electronic Actuators:** Control of alarms, lighting, and access-related devices.
- **IP Cameras / Local Area Network (LAN):** Video monitoring over the local network.

## Project Goals

- Demonstrate practical **hardware–software integration** in an electronic security system.
- Develop a centralized application for monitoring sensors and controlling connected devices.
- Explore communication between a desktop application and embedded hardware.
- Investigate wireless connectivity to support future distributed security substations.
- Gain practical experience in embedded programming, electronic interfacing, system integration, testing, and troubleshooting.

## Project Status

The original 2022 capstone implementation and later wireless development experiments represent different stages of the project.

The repository preserves the original application and embedded code, alongside supporting materials and subsequent experimental development where available.

## License

Copyright © 2022 Haeytham Al Malak.

All rights reserved. Unauthorized use, reproduction, or modification of this project is strictly prohibited.
