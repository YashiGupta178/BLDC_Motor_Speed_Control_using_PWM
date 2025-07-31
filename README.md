# PWM Control of a BLDC Motor
### Copyright 2019 The MathWorks, Inc.

This repository contains MATLAB and Simulink files used in the [How to Design Motor Controllers Using Simscape Electrical, Part 5: An Alternative Implementation of PWM Control](https://www.mathworks.com/videos/how-to-design-motor-controllers-using-simscape-electrical-part-5-an-alternative-implementation-of-pwm-control-1579758063226.html) video. Check out the rest of the videos in [this section](#videos-and-files).

## Model and Setup
In the Simulink model which is shown in the following snapshot, the three-phase voltages are modulated directly using PWM that is implemented under the commutation logic subsystem. 

![](images/model.png)

You can run the Simulink model by pressing the “Run” button on the simulation tab and then use the data inspector to view the logged signals such as desired and measured speeds, DC source voltage and three-phase voltages supplied to the BLDC motor.



