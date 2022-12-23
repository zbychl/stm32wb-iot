# iot-boards
This repisitory is to keep designs for IoT boards,e.g for IoT sensors, effectors, bridges, etc. 

## Boards
Below there is a list of designed boards

### Board 1 - IoT sensor/effector with STM32WB
Board designed for IoT sensor or effector. It is based on STM32WB SoC. Board design supports components listed below. Some of them are optional. 

#### Components:
* STM32WB55CGU6 - dual ARM SoC with radio (BLE and IEEE 802.15.4)
* SHTC3 - digital (I2C) temperature and humidity sensor
* Switch(es)
* PCB antenna
* CR2032 battery socket
* Pins for external power supplier
* Test Points (TPs) for UART for update
* TPs for UART for console
* TPs for JTAG
* TP for HW reset
* LED(s) for health/status monitoring
* GPIO exposed on pins to support common interface (I2C, SPI, UART) 

#### PCB details
There is a list of requirements put for PCB:
* Size: tbd
* Stackup:
  * https://jlcpcb.com/impedance
  * Layers: 4
  * Width: 1.6mm
  * Prepeg: 7628 (Fr=4.6)
* Standard SMT elements size: 0402 

### Board 2
TBD

