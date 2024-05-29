![image](https://github.com/acam4890/RSLogix-Simulation-Projects/assets/130267975/cc9d1fe3-6498-4fc4-83fb-577342c97491)

Looks a bit more complicated than it is. This program controls two hoppers (one filled with pecans and the other with walnuts) and a converyor belt motor with the help of multiple sensors. A box is sent down 
a converyor belt when the PLC energizes the motor. The motor stops being energized once the box reaches the proximity sensor. The box is now underneath the two hoppers and in front of two photoelectric sensors.
The photoelectric sensors determine if the label on the box is blue (walnuts) or red (pecans). Using this information, the PLC program will open the correct hopper and range sensor will check the depth of box
to determine if the level of nuts inside has filled the box. Once the box is full, the hopper is closed and the conveyor motor is re-energeized. The filled box is sent out and the next empty box is brought up
to the proximity sensor.
