# Embedded_basics
These projects are simulated on wokwi simulator. All the projects are programmed using register addressing without using libraries for lcd or keypad.
Datasheet provides the ports are addresses for the peripherals which you want to use.
1) Timer 0-60 seconds:
->To check out the project, visit this link: https://wokwi.com/projects/434474126926223361
->Wait for the LCD to load. Enter a number between 0-60 , after the timer the buzzer will ring.
->Press A to display the entered number , press D to start the timer.
->I have used portk , portf for the LCD; porta for the keypad ; some pins from porte for buzzer.
->Timers 1,3,5 were used for delay,buzzer,timer_count respectively.

