# Smart UPS SNMP WiFi Card <img src="https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/blob/main/Images/Ukraine.png" height=24> <img src="https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/blob/main/Images/3d.png" height=200 style="float: right;">

[![GitHub release](https://img.shields.io/github/release/AleksandrBraun/Smart-UPS-SNMP-Card/all.svg)](https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/releases "Releases") [![GitHub issues](https://img.shields.io/github/issues/AleksandrBraun/Smart-UPS-SNMP-Card)](https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/issues) [![Github All Releases](https://img.shields.io/github/downloads/AleksandrBraun/Smart-UPS-SNMP-Card/total.svg)](https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/tree/main/Firmware) [![repo size](https://img.shields.io/github/repo-size/AleksandrBraun/Smart-UPS-SNMP-Card.svg)](https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card)

WiFi network card support project for Smart UPS APC, etc.

<img src="https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/blob/main/Images/HASS.png" height=48>&nbsp;&nbsp;&nbsp;<img src="https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/blob/main/Images/APC.svg" height=48>

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

#### [Documentations](Docs/en/Interface.md)
#### [Описание](Docs/ru/Interface.md)

### Several screenshots

<div align="center">

  <img src="https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/blob/main/Images/Main-Control.png">

### 
---
  <img src="https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/blob/main/Images/Settings.png">

### 
---
  <img src="https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/blob/main/Images/Alert-Error.png">

### 
---
  <img src="https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/blob/main/Images/Network-MQTT-SSH.png">

### 
---
  <img src="https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/blob/main/Images/Fan-Control.png">

### 
---
  <img src="https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/blob/main/Images/FWUpdate-page.png">

### 
---
  <img src="https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/blob/main/Images/hass_card.png">

### 
---
  <img src="https://github.com/AleksandrBraun/Smart-UPS-SNMP-Card/blob/main/Images/hass_discovery.png">

</div>
