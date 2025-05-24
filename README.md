## Features
Arm-Based Controller:
- Bootloader and Target Application: Handles bootloader commands and provides a seamless interface.
- Main Application: Operates in standard mode but can transition to bootloader mode when prompted by the Raspberry Pi.

Raspberry Pi 4:
- Employs the Yocto build system to construct a custom image.
- Configures the kernel and Wi-Fi for network connectivity.
- Supports network file system booting for development purposes.
- Includes a C++ host-bootloader to manage update commands.

## Key Points
- Enables remote OTA updates with Arm-Based Controller, Raspberry Pi 4, and GitHub.
- Provides efficient and seamless software updates for connected devices.
- Encourages community collaboration for ideas and contributions to enhance the system.

## Baremetal Bootloader Sequence Diagram

![Baremetal Bootloader Sequence Diagram](https://github.com/jeremynguyenn/Firmware-Over-The-Air-Update-Implementation-with-STM32-Raspberry-Pi-4./blob/main/Firmware%20Over%20The%20Air%20Stm32%20and%20RaspberryPi/demopicvid/BaremetalBootloaderSequenceDiagram.png)

## Monitoring Mode Sequence Diagram

![Monitoring Mode Sequence Diagram](https://github.com/jeremynguyenn/Firmware-Over-The-Air-Update-Implementation-with-STM32-Raspberry-Pi-4./blob/main/Firmware%20Over%20The%20Air%20Stm32%20and%20RaspberryPi/demopicvid/MonitoringModeSequenceDiagram.png)

## CLI Mode Sequence Diagram

![CLI Mode Sequence Diagram](https://github.com/jeremynguyenn/Firmware-Over-The-Air-Update-Implementation-with-STM32-Raspberry-Pi-4./blob/main/Firmware%20Over%20The%20Air%20Stm32%20and%20RaspberryPi/demopicvid/CLI%20Mode%20Sequence%20Diagram.png)
