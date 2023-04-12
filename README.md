# Smart UPS SNMP WiFi Card
WiFi network card support project for Smart UPS APC, etc.

![](https://img.shields.io/github/release/AleksandrBraun/Smart-UPS-SNMP-Card.svg) ![](https://img.shields.io/github/issues/AleksandrBraun/Smart-UPS-SNMP-Card.svg)

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
- The presence of SSH to send a command to an external server (shutdown, run bat, etc.)
- Based on protocol from APC SNMP cards
