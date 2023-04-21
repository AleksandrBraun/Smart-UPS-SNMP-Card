In standard mode, the UPS turns on the fan at low speed in a constant mode. Even when operating from the mains without using an inverter and the output switches are quite cool, the fan makes quite noticeable noise. Before the UPS transitions to battery operation, there is little point in cooling a non-working inverter.
By warming up the inverter keys, it is possible to adjust the air flow for cooling dynamically, depending on the temperature level.

Changing the fan speed control requires a very simple operation.

![изображение](https://user-images.githubusercontent.com/36089626/233575888-dbd3d089-dbb8-47d5-ab23-afa7a9bb5501.png)

1. Drill a 3-4 mm hole in the plastic case in which the module is installed to lead the wires out of the case. Run wires through it.
2. Disconnect the black wire from the stock fan connector.
3. Connect it to the red wire coming from the module
4. Screw the black wire to the UPS ground (you can simply put it under the fan mount and press it with the fan screw or under the standard ground screw)

Next, you can make some settings for the cooling mode.

![Cooling](https://user-images.githubusercontent.com/36089626/233565434-42f7a404-608b-4a97-8579-b6f2f83057cd.png)

1. The minimum level of PWM (voltage) on the fan, at which it begins to rotate
    - It is necessary to test the minimum for the start of rotation when the lower temperature threshold in the UPS is exceeded. Depends on the type of fan, its degree of wear, etc.
    - The test button runs the fan at the specified PWM level for 10 seconds. If the fan does not start, you need to raise the PWM level above
2. Temperature at which to start UPS forced cooling
3. Temperature at which the fan will rotate at maximum speed
