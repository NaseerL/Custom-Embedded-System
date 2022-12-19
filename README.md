# Custom-Embedded-System
This is an embedded system completely made from scratch. This embedded system consists of two MSP430G2553 chips, two buttons, one ultrasonic sensor,
one accelerometer, one buzzer, one Quad-digit 7 segment LED and one voltage regulator and a battery pack. First when powered on, 
the LED displays 5 values and one of these five values can be selected using the first button. THe LED displays ultrasonic sensor values in cm.
When an object is at the same distance as chosen by the user using the button, the buzzer buzzes. THe buzzer using PWM to buzz at different volumes.
When the user selects a small distance the buzzer is louder but as the number gets higher the buzzer gets lower.Then clicking on button two, switches to accelerometer.
THe LED now shows the x and y axis values on a 0-90deg scale. When the embedded system is laid down flat, i.e. x-axis is 0deg and y-axis is is 0deg the buzzer
buzzes. The two MSP430G2553 communicate to each other using UART. Interrupts have been used for buttons, timers for ultrasonic sensor and ADC for accelerometer.
Finally everything has been soldered on a perf board.



![dd](https://user-images.githubusercontent.com/82166449/208484746-311a2613-f352-474b-88a0-b57596f25dcb.png)
