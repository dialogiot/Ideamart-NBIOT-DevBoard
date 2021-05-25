### About the Board

The board is developed based on the [SIM7000C](http://www.simcomm2m.com/En/module/detail.aspx?id=167) and [SIM7000E](http://www.simcomm2m.com/En/module/detail.aspx?id=168) Modules as well as the Microcontroller ATMega 328 based on the most popular Arduino UNO PIN layout. Therefore this board is compatible with any shield that is compatible with the Arduino UNO

### Distribution
Any one can destribute or modify this deign. but originated souce should be published

### NB-IOT /GPS sample and SDK
[https://github.com/dialogiot/Dialog_NB-IOT_CAT-M](https://github.com/dialogiot/Dialog_NB-IOT_CAT-M)



#### Drivers

Download the [USB Drivers](https://github.com/botletics/SIM7000-LTE-Shield/wiki/SIM7000-USB-Drivers)
Note: Windows 10 users should use the Windows 8 Drivers

<img src="https://idealab.ideamart.io/NBIOT-Dev-Board/img/features/board-diagram.jpg" width="800"></img>

[View Image](https://idealab.ideamart.io/NBIOT-Dev-Board/img/features/board-diagram.jpg)

|No|PIN |Description|
|---|---|---|
| 1 | USB Port | Programing USB port for ATMEL Chip - PC driver may be required. Use Arduino USB cable or USB printer wire to connect with PC |
| 2 | FTDI | FTDI USB to Serial Converter FT232RL chip |
| 3 | LED2 | User programable LED |
| 4 | PIN Headers | Programable PIN headers to connect with micro controller. (Diagram 2 for more details) |
| 5 | Level Shifter | 1.8V to 5V voltage level shifter |
| 6 | SIM7000 | SIM7000 NB-IOT/eMTC/GSM/LTE Modem and GNSS Receiver |
| 7 | RF Antenna | RF mobile network antenna port for SIM7000 (u.fL) |
| 8 | GPS Antenna | GPS signal antenna port for SIM7000 (u.fL) |
| 9 | PPTC | PPTC resettable fuse for USB input over current protection (max 500mA) |
| 10 | DC Input | 2.1mm 7-12V DC power input |
| 11 | RESET | ATMEGA328P micro controller reset button |
| 12 | 3.3V Regulator | Lm1117 3.3V low dropout linear regulator (max 800ma)|
| 13 | 5V Regulator | LM1117 5V low dropout linear regulator (max 800mA) |
| 14 | PIN Headers | Programable PIN headers to connect with micro controller.(Diagram 2 for more details) |
| 15 | ATMEGA328P | ATMEGA328P micro controller |
| 16 | Power LED | Power indicator LED |
| 17 | ICSP Header | ICSP Header for Arduino programming |
| 18 | Modem Reset | SIM7000 modem hardware reset button |
| 19 | STAT LED | SIM7000 modem STAT LED indicator |
| 20 | Modem USB | SIM7000 modem USB port - firmware upgrade - Modem debug |
| 21 | PWR KEY | SIM7000 modem power key - Press 1.5sec to power up/down |
| 22 | Net Light | Power indicator LED |


## 2 What you Should know about the board

- ATMEGA328P µCU with FTDI USB to serial converter
- Same pinout as Arduino UNO
- Compatible with any Arduino UNO shield
- Programable with Arduino IDE
- NB-IoT/GSM/LTE/eMTC enabled SIM7000C/SIM7000E module onboard
- Separate USB interface for SIM7000 module
- GNSS (GPS,GLONASS and BeiDou/Compass, Galileo, QZSS)enabled 

> Separate USB interface can only be used for SIM7000 debug and firmware upgrades

- SIM7000C FDD-LTE B1/B3/B5/B8
- SIM7000E Tri-Band FDD-LTE B3/B8/B20/B28
- GSM/GPRS/EDGE 900/1800 MHz
- GNSS (GPS,GLONASS and BeiDou/Compass, Galileo, QZSS)
- LTE CAT-M1(eMTC) Uplink up to 375kbps, Downlink up to 300kbps
- NB-IoT Uplink up to 66kbps, Downlink up to 34kbps
- EDGE Class Uplink up to 236.8Kbps, Downlink up to 236.8Kbps
- GPRS Uplink up to 85.6Kbps, Downlink up to 85.6Kbps

