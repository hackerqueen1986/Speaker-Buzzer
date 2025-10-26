Components
* Raspberry Pi: Any model with GPIO pins. 
* Buzzer: An active buzzer (which makes a single tone) or a passive buzzer (which can be controlled to make different pitches). 
* Jumper Wires: To connect the buzzer to the Pi. 
* Breadboard: For easy and temporary connections. 
(For passive buzzers) Transistor: To amplify the signal from the GPIO pin, as GPIO pins are not designed to power high-current devices. 
(For passive buzzers) Resistor: A 1kΩ resistor is often used to protect the GPIO pin. 



Basic software (Python)
1.You can use libraries like RPi.GPIO or gpiozero to control the buzzer. 
2.For a passive buzzer, use Pulse Width Modulation (PWM) to change the frequency and create different tones. 
3.The code will tell the GPIO pin to turn on for a certain duration and at a specific frequency, and then turn off. 

