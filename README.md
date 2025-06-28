# Embedded_basics
These projects are simulated on wokwi simulator. All the projects are programmed _**using register addressing without using libraries**_ for lcd or keypad.
_**Datasheet**_ provides the ports are addresses for the peripherals which you want to use.


1)Timer 0-60 seconds:
---------------------
To check out the project, visit this link: https://wokwi.com/projects/434474126926223361

->Wait for the LCD to load. Enter a number between 0-60 , after the timer the buzzer will ring.

->Press A to display the entered number , press D to start the timer.

->I have used portk , portf for the LCD; porta for the keypad ; some pins from porte for buzzer.

->Timers 1,3,5 were used for delay,buzzer,timer_count respectively.


2)Temperature read using analog sensor: 
---------------------------------------
To check out the project, visit this link: https://wokwi.com/projects/429045621319436289

->LCD and Temperature sensor are being used to display the analog value of the sensor(with respect to temperature).

->Load the project, wait for hello world to print on the LCD. 

->click on the sensor to load its drag bar to adjust the temperature. The LCD will show the analog value with respect to the drag bar position.
The values are not mapped but can be easily done using the formula: mapped_value = (analog_value * max_temperature_value) / max_analog_sensorvalue

->ADC peripheral was used to make this project. The temperature values are converted to string before being printed on LCD.

3)2-digit counter:
------------------
To check out the project, visit the link: https://wokwi.com/projects/426967610171012097

->7segment display , buttons were used to make it.

->The displaying of numbers after 10 was a tricky part of the project. The display are refreshed at a rate which is not perceivable to the human eye, but 
at a given time only one of the displays are on.

->Green button is used to increment and red button is used to reset the value.


