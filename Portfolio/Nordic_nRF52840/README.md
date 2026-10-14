# Nordic BLE Hardware & Firmware Engineering

**Hardware design · Embedded C · Zephyr RTOS / nRF Connect SDK · Bluetooth LE · Manufacturing · Validation**

[**View the current Nordic BLE Engineering Portfolio (v14 PDF)**](Nordic_BLE_Engineering_Portfolio_Green_Style_v14.pdf)

## Overview

This portfolio documents Nordic nRF52840 embedded hardware design and complementary Nordic firmware development, from circuit architecture and KiCad PCB layout to manufacturing handoff, custom Bluetooth LE services and live sensor-to-application validation.

The project combines custom nRF52840 PCB engineering and manufacturing preparation with Zephyr/nRF Connect SDK firmware, custom BLE GATT services and live sensor-to-application demonstrations on physical Nordic development hardware.

## Hardware and PCB engineering

- Custom nRF52840-based wireless sensor and GNSS hardware designed in KiCad, with modular I²C, SPI, UART and GPIO expansion.
- Single-cell LiPo supply with TPS63802 buck-boost regulation to the 3.3 V system rail.
- MAX-M10S GNSS with external active antenna interface; NFC, SWD programming/debug and test access.
- ADXL372 high-g motion sensing, BME688 environmental sensing and VEML6035 ambient-light integration in the hardware design.
- Hierarchical schematic design, PCB placement and routing, and DFM/DFT review.
- Gerber/drill files, BOM, CPL/pick-and-place data, sourcing checks and JLCPCB assembly quotation-stage review.

## Firmware, BLE and application validation

- Modular embedded C developed with Zephyr RTOS and Nordic nRF Connect SDK, including Devicetree/Kconfig, sensor drivers, logging and persistent settings.
- Physical Nordic development-hardware tests with BME680 environmental sensing and BH1750 ambient-light sensing.
- Custom 128-bit BLE GATT service with READ/NOTIFY environmental characteristics, client subscriptions and a writable update interval.
- EnviroVue browser-based BLE client demonstrating live measurements, trends and bidirectional device configuration.

## Engineering evidence

The PDF brings together schematic and PCB design, manufacturing outputs, firmware source and logs, BLE service implementation, and photographs/screenshots of physical Nordic development hardware and the connected application.

[**Open the current portfolio PDF**](Nordic_BLE_Engineering_Portfolio_Green_Style_v14.pdf)


[Back to the portfolio index](../README.md)
