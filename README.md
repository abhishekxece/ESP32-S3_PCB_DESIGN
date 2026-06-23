# ESP32-S3_PCB_DESIGN
Custom ESP32-S3-MINI-1 breakout board designed in KiCad.

## Overview

This project is a custom breakout board designed around the **ESP32-S3-MINI-1** module using **KiCad**. The objective was to create a compact and easy-to-use development board that exposes the ESP32-S3's GPIOs while integrating the essential power, programming, and peripheral circuitry required for embedded system development.

The PCB was designed completely from scratch, including the schematic capture, component placement, PCB layout, and manual routing.

## Board Functionality

The board is powered through a **USB Type-C** connector, which serves as the primary power input. An onboard **3.3V Low Dropout (LDO) Voltage Regulator** provides a stable supply voltage required by the ESP32-S3 module and other onboard peripherals.

A dedicated **temperature and humidity sensor (ENS210)** is integrated into the design, enabling environmental sensing without the need for external modules. This makes the board suitable for IoT applications involving environmental monitoring and data acquisition.

All major **GPIO pins** of the ESP32-S3 are broken out to standard pin headers, allowing easy interfacing with external sensors, displays, communication modules, and other embedded peripherals.

The board also includes dedicated **BOOT** and **RESET** push buttons to simplify programming and debugging during firmware development.

Special attention was given to USB signal routing, power distribution, component placement, and PCB layout to ensure a clean and manufacturable design. The USB differential data lines were manually routed, and the entire PCB was completed without using an autorouter.

## Features

* ESP32-S3-MINI-1 based custom breakout board
* USB Type-C power interface
* Onboard 3.3V LDO voltage regulator
* Integrated ENS210 temperature and humidity sensor
* GPIO breakout headers for external peripherals
* BOOT and RESET push buttons
* Two-layer PCB designed in KiCad
* Fully hand-routed PCB layout
* Manufacturing-ready Gerber files included

## Tools Used

* KiCad (Schematic Capture & PCB Design)
* Git & GitHub (Version Control)

## Author

**Abhishek Mohammad**
B.Tech, Electronics and Communication Engineering
National Institute of Technology Jalandhar
