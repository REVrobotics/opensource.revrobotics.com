Open source software published by REV Robotics

## Software that ships on REV hardware

### Control Hub

<details>
  <summary>Control Hub Linux kernel</summary>

[Linux kernel for Control Hub OS 1.0.0](https://github.com/REVrobotics/kernel-controlhub-android/tree/ch-os-1.0.0)

[Linux kernel for Control Hub OS 1.0.1](https://github.com/REVrobotics/kernel-controlhub-android/tree/ch-os-1.0.1)

[Linux kernel for Control Hub OS 1.1.0](https://github.com/REVrobotics/kernel-controlhub-android/tree/ch-os-1.1.0)

[Linux kernel for Control Hub OS 1.1.1](https://github.com/REVrobotics/kernel-controlhub-android/tree/ch-os-1.1.1)
(same as 1.1.0)

[Linux kernel for Control Hub OS 1.1.2](https://github.com/REVrobotics/kernel-controlhub-android/tree/ch-os-1.1.2)
</details>

<details>
  <summary>Control Hub U-Boot bootloader</summary>

[Bootloader for Control Hub OS 1.0.0](https://github.com/REVrobotics/u-boot-controlhub-android/tree/ch-os-1.0.0)

[Bootloader for Control Hub OS 1.0.1](https://github.com/REVrobotics/u-boot-controlhub-android/tree/ch-os-1.0.1)
(same as 1.0.0)

[Bootloader for Control Hub OS 1.1.0](https://github.com/REVrobotics/u-boot-controlhub-android/tree/ch-os-1.1.0)

[Bootloader for Control Hub OS 1.1.1](https://github.com/REVrobotics/u-boot-controlhub-android/tree/ch-os-1.1.1)
(same as 1.1.0)

[Bootloader for Control Hub OS 1.1.2](https://github.com/REVrobotics/u-boot-controlhub-android/tree/ch-os-1.1.2)
(same as 1.1.0)
</details>

### Driver Hub
<details>
  <summary>Driver Hub Linux kernel</summary>

[Linux kernel for Driver Hub OS 1.0.0](https://github.com/REVrobotics/kernel-driverhub-android/tree/dh-os-1.0.0)

[Linux kernel for Driver Hub OS 1.0.1](https://github.com/REVrobotics/kernel-driverhub-android/tree/dh-os-1.0.1)
(same as 1.0.0)

[Linux kernel for Driver Hub OS 1.0.2](https://github.com/REVrobotics/kernel-driverhub-android/tree/dh-os-1.0.2)
(same as 1.0.0)
</details>

<details>
  <summary>Driver Hub U-Boot bootloader</summary>

[Bootloader for Driver Hub OS 1.0.0](https://github.com/REVrobotics/u-boot-driverhub-android/tree/dh-os-1.0.0)

[Bootloader for Driver Hub OS 1.0.1](https://github.com/REVrobotics/u-boot-driverhub-android/tree/dh-os-1.0.1)

[Bootloader for Driver Hub OS 1.0.2](https://github.com/REVrobotics/u-boot-driverhub-android/tree/dh-os-1.0.2)
(same as 1.0.1)
</details>

<details>
  <summary>Driver Hub keyboard (OpenBoard)</summary>

[Driver Hub OpenBoard 1.4.3-1](https://github.com/REVrobotics/openboard/tree/v1.4.3-1)
</details>

<details>
  <summary>Driver Hub Software Manager</summary>

Based on the [Foxy Droid](https://github.com/kitsunyan/foxy-droid/) F-Droid client

[Driver Hub Software Manager 1.0.1](https://github.com/REVrobotics/Driver-Hub-Software-Manager/tree/dhsm-1.0.1)

[Driver Hub Software Manager 1.0](https://github.com/REVrobotics/Driver-Hub-Software-Manager/tree/dhsm-1.0)
</details>

## Example code
### Using the REV Color Sensor V3 in FRC
Code samples for how to use a REV Color Sensor V3 in WPILib
[Color-Sensor-v3-Examples](https://github.com/REVrobotics/Color-Sensor-v3-Examples)

### Using the SPARK MAX with a RoboRIO
Code samples for how to use a SPARK MAX in WPILib

[SPARK-MAX-Examples](https://github.com/REVrobotics/SPARK-MAX-Examples)

## Libraries for communicating with REV hardware
### Color Sensor V3 FRC driver
The full source code of the REV Color Sensor V3 driver for WPILib

[Color-Sensor-v3](https://github.com/REVrobotics/Color-Sensor-v3)

### CANBridge
[CANBridge](https://github.com/REVrobotics/CANBridge) is a Windows library to allow PC applications
to connect to the FRC CAN bus using supported REV Hardware.

### node-can-bridge
A node.js/Electron library that exposes a Javascript API for the CANBridge library, for use with
node.js and Electron applications

[node-can-bridge](https://github.com/REVrobotics/node-can-bridge)

### node-expansion-hub-ftdi
A node.js/Electron library that can put USB-connected Expansion Hubs into firmware update mode

[node-expansion-hub-ftdi](https://github.com/REVrobotics/node-expansion-hub-ftdi)

## Device firmware
### REV Blinkin LED Driver firmware
The full Arduino firmware for the REV Blinkin LED driver. Using modified firmware on your Blinkin
may not be legal for FTC competition use.

[Blinkin-Firmware](https://github.com/REVrobotics/Blinkin-Firmware)

## Assorted projects
### FTC Robocol Wireshark plugin
Wireshark is a network packet analysis tool, and we developed a
[Wireshark plugin](https://github.com/REVrobotics/FTC-robocol-Wireshark-plugin) that allows you to
analyze the FTC network traffic (called Robocol) between the Robot Controller and Driver Station
apps. For this to work, you must know the password to the robot's WiFi network.

[FTC-robocol-Wireshark-plugin](https://github.com/REVrobotics/FTC-robocol-Wireshark-plugin)

### DfuSeFile
A library for reading and writing DFU files in the DfuSe format

[DfuSeFile](https://github.com/REVrobotics/DfuSeFile)
