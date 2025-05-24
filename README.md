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

![Baremetal Bootloader Sequence Diagram](https://github.com/t0ti20/FOTA/assets/61616031/df4a67b1-1b05-4a3d-a45a-551b7a5aa260)

## Monitoring Mode Sequence Diagram

![Monitoring Mode Sequence Diagram](https://github.com/t0ti20/FOTA/assets/61616031/8cf64c10-93fd-45c8-b06c-dbf67f9d5059)

## CLI Mode Sequence Diagram

![CLI Mode Sequence Diagram](https://github.com/t0ti20/FOTA/assets/61616031/58ea119d-830d-42a8-bc0e-6e340c33fd20)
