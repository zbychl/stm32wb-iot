# STM32WB based IoT Project
This repisitory keeps components for IoT project based on STM32WB SoC. Project could be used as IoT sensor, effector, bridge, etc. 

# Project Components
Below there is a list of project components along with their description (PCB design for IoT board - HW, firmware - FW, software - SW, and documentation - DOC) . 

## HW - IoT board based on STM32WB SoC
Board designed for IoT sensor or effector. It is based on STM32WB SoC. Board design supports components listed below. Some of them are optional. 

### HW Components:
* STM32WB55CGU6 - dual ARM SoC with radio (BLE and IEEE 802.15.4)
* SHTC3 - digital (I2C) temperature and humidity sensor
* Switch(es)
* PCB antenna
* CR2032/LIR2032 or CR3032/LIR3032 battery socket
* Pins for external power supplier
* Test Points (TPs) for UART for update
* TPs for UART for console
* TPs for JTAG
* TP for HW reset
* LED(s) for health/status monitoring
* GPIO exposed on pins to support common interface (I2C, SPI, UART) 

### PCB details
There is a list of requirements put for PCB:
* Size: tbd
* Stackup:
  * https://jlcpcb.com/impedance
  * Layers: 4
  * Width: 1.6mm
  * Prepeg: 7628 (Fr=4.6)
* Standard SMT elements size: 0402 

## FW
TBD

## SW
TBD

## DOC
TBD

