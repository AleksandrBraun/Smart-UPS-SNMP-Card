![System](https://user-images.githubusercontent.com/36089626/233394935-ebecc1b5-b702-44e4-820f-382692825dc1.png)

1. Enabling the communication protocol with UPS
     - When the protocol is disabled, communication via standard UPS outputs is activated. RS232 or USB
2. Activation of an external temperature sensor
3. Select the type of sensor. Based on 10k NTC thermistor (β coef. 3950) or Dallas DS18B20 temperature sensor
4. The period of updating data in the web page.
5. UPS Live Data Request Period
     - Battery voltage
     - Load current
     - Reactive load power
     - Temperature of MOSFET inverters
     - Output power in %% of UPS power
     - Battery level in %%
6. UPS Status Request Period
7. Request period for infrequently updated data
     - Line frequency
     - Mains input voltage
     - Maximum mains voltage from the last switch on
     - Minimum mains voltage from last switch on
     - Mains output voltage from UPS
     - Result of the last self-test
8. Button for local saving of user settings
9. Button to restore the saving of user settings
10. Select a saved settings file

SAVE button for saving settings to the non-volatile memory of the module.

![Thermoprobe](https://user-images.githubusercontent.com/36089626/233596425-2dd7d895-65a6-4d8a-b1b6-533186b60944.png)

The DS18B20 sensor is connected as shown in the picture.

10k thermistor, connected to the GND and SIGNAL pins. In this case, the +3.3V connector output is not used.
