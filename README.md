# Speed Control of DC Motor Using PWM

## Aim

To control the speed of a DC motor using Pulse Width Modulation (PWM) with a development board.

## Algorithm

1. Initialize the development board and set the motor control pin as an output.
2. Generate a PWM signal at the required frequency.
3. Set an initial PWM duty cycle.
4. Apply the PWM signal to the DC motor through a suitable motor driver.
5. Vary the duty cycle to increase or decrease the motor speed.
6. Observe the corresponding change in motor speed.
7. Repeat the process for different duty-cycle values.

## Procedure

1. Connect the DC motor to the motor driver circuit.
2. Connect the motor driver to the development board.
3. Connect the required power supply and ensure a common ground.
4. Configure the motor control pin for PWM output.
5. Upload the PWM motor-control program to the development board.
6. Start the motor with a low PWM duty cycle.
7. Gradually increase the duty cycle and observe the increase in motor speed.
8. Decrease the duty cycle and observe the reduction in motor speed.
9. Record the motor response for different PWM values.

## Result

<img width="1537" height="746" alt="image" src="https://github.com/user-attachments/assets/fa5de145-628b-48cd-83c4-d79f3d3bbac8" />

<img width="1340" height="727" alt="image" src="https://github.com/user-attachments/assets/4e4ac2e4-c6be-4502-99f3-d876d1987fb0" />

The speed of the DC motor was successfully controlled using PWM. Increasing the PWM duty cycle increased the motor speed, while decreasing the duty cycle reduced the motor speed.

