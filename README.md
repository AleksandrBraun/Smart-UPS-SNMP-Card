# Smart UPS SNMP WiFi Card <img src="https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/blob/main/Images/Ukraine.png" height=24> <img src="https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/blob/main/Images/3d.png" height=200 style="float: right;">

[![GitHub release](https://img.shields.io/github/release/AleksandrBraun/Smart-UPS-SNMP-Card/all.svg)](https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/releases "Releases") [![GitHub issues](https://img.shields.io/github/issues/AleksandrBraun/Smart-UPS-SNMP-Card)](https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/issues) [![Github All Releases](https://img.shields.io/github/downloads/AleksandrBraun/Smart-UPS-SNMP-Card/total.svg)](https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/tree/main/Firmware) [![repo size](https://img.shields.io/github/repo-size/AleksandrBraun/Smart-UPS-SNMP-Card.svg)](https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card)

WiFi network card support project for Smart UPS APC, etc.

<img src="https://user-images.githubusercontent.com/36089626/233591378-432f1a4e-89f6-49d9-9716-f451cfbe7b46.png" height=48>&nbsp;&nbsp;&nbsp;<img src="https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/blob/main/Images/APC.svg" height=48>

Attempt to replace the standard APC Smart UPS network monitoring card.
The card is designed for remote monitoring of the UPS status over a WiFi network.
Connecting to UPS is done using a web interface in a browser or smartphone.
UPS management is also provided.

### Features

- Works with a direct connection to the card by DNS name or IP
- Setting up a connection to a WiFi access point
- Connecting to an MQTT broker
- MQTT management
- Home Assistant discovery support
- The presence of SSH to send a command to an external server (shutdown, run bat, ran com, etc.)
- Based on protocol from APC SNMP cards

### Optional
- Dynamic fan speed control*
- Remote temperature sensor for monitoring external batteries, etc.**
> *requires tampering with the UPS case for minimal rework

> **external temperature sensor required (NTC or DS18B20)

### Future additions
- Connecting a remote graphic / text display
- Sending an event report to a remote mail server
- Output port expander for controlling external devices *
- Data logging to internal flash memory for further analysis *
> *will be implemented in the next hardware generation

###### Official list of supported devices (tested on APC Smart UPS 1000XL *SUA 1000 XLI*) <a href="https://www.apc.com/us/en/faqs/FA237786/" title="APC site">link</a>

![Preview](https://user-images.githubusercontent.com/36089626/233600427-206662c7-9491-4d23-a2b2-eb5a41ec2a1c.png)

#### [Documentations](Docs/en/Interface.md)
#### [Описание](Docs/ru/Interface.md)
> __Note__
>
> Changes are taking place on an ongoing basis. Some screenshots may not match the updated data. Screenshots will be updated when there are enough changes.
>
> Изменения происходят в постоянном режиме. Некоторые скриншоты могут не соответствовать обновленным данным. Скриншоты будут обновляться при достаточном колличестве изменений.

### Several screenshots

<div align="center">

  ![Pic_1](https://user-images.githubusercontent.com/36089626/233590130-a3be8847-fc84-4377-8c7b-e3227e5f6b7f.png)

### 
---
  ![Pic_2](https://user-images.githubusercontent.com/36089626/233590306-a57e5a5a-430a-4834-857c-6972f3e184c3.png)

### 
---
  ![Pic_3](https://user-images.githubusercontent.com/36089626/233590356-48457353-9b26-4da2-89de-784364373f12.png)

### 
---
 ![Pic_4](https://user-images.githubusercontent.com/36089626/233590402-cf2a3a65-e76f-4f70-83ab-7dd6c3a0a2b6.png)

### 
---
  ![Pic_5](https://user-images.githubusercontent.com/36089626/233590468-2e1244a2-6915-49bd-a9c3-8866eecb1465.png)

### 
---
  ![Pic_6](https://user-images.githubusercontent.com/36089626/233590510-03b71d0a-2ee0-4f1e-9754-a1bbf42c0e87.png)

### 
---
  ![Pic_7](https://user-images.githubusercontent.com/36089626/233590553-215e7b7d-4289-4787-95f6-d808aea5b59c.png)

### 
---
  ![Pic_8](https://user-images.githubusercontent.com/36089626/233590611-66ac061e-9fdf-4428-8d75-6a63250fea7d.png)

</div>
