![Interface](https://user-images.githubusercontent.com/36089626/233385226-a341ce70-9e1e-4eea-aadd-7f018a8805f8.png)

1. Information about UPS
2. Tab menu
    - [Control](Control.md)
    - [System settings](System.md)
    - Errors, Alert, Statuses
    - Network settings
    - Fan settings
    - Manual update
    - Reboot module
3. UPS command response window
4. Operational summary of UPS parameters
5. Main interface window

### 
---
Communication with the UPS takes place using the Simple Network Management Protocol, or SNMP for short.

The module manages the main UPS functions using this protocol.

Also, some limited actions with UPS, the module can perform directly by itself.

These include the following commands:
- Turn on output UPS
- Turn off output UPS
- Run Self Test
- Check current battery voltage
- Disable module communication with UPS (allow external connection to UPS via RS232 or USB)

The firmware allows you to flexibly configure the functionality of the SNMP module for user preferences.

The module has a WEB interface in HTML, JS and AJAX accessible by IP or DNS name.

The following functionality is currently implemented:
1. Monitoring the current state of UUPS
     - Voltage of the incoming network
     - UPS output voltage
     - Battery voltage in volts and %%
     - Battery voltage directly at the battery terminals (can be monitored even if the exchange protocol with UPS is not working / disabled)
     - Maximum / minimum input voltage for the period from the last switch on
     - Delivered power during battery operation in %% of the rated power of the UPS
     - Internal inverter temperature
     - Temperature at the external sensor (connection of an external temperature sensor NTC 10k or Dallas DS18B20 is required)
     - Diagnosis and control of all warnings / statuses / errors from UPS

2. UPS Mode Management
     - Turn on / off the UPS output even if there is no communication via the communication protocol
     - Active WiFi hotspot in the module (name/password, hidden/visible)
     - Local WiFi connection (DHCP / Static IP / Port selection)
     - Connection to MQTT broker (control/management)
     - Integration into Home Assistant (HASS Discovery)
       * New firmware notification and update from Home Assistant interface
     - Execute commands on a remote server via SSH (login / password)
     - Setting the cooling fan speed depending on the temperature of the internal MOSFET of the inverter. (requires minimal intervention in connecting the cooler to the UPS)
     - Setting up UPS polling intervals to get the required response time
       * Operational requests
       * Request statuses
       * Query rarely modified data
     - Saving and restoring user settings before manually updating firmware

