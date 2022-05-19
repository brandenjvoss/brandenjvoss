# My Portfolio
This portfolio is intended to display some projects I have worked on through personal interest, work experience and school in a convenient way.
## About Me
Currently, I'm an electrical engineering student in my fourth year at the University of Victoria. Through this GitHub profile, I hope to express my passion for the projects I have been involved in and my desire to improve myself and those around me.
<br/><br/>Check out my LinkedIn profile here:
<br/><br/>
[![][linkedInIcon]](https://www.linkedin.com/in/bjvoss/)

[linkedInIcon]: https://github.com/cgriffs/image_icons/blob/main/IconFolder/socialsicons/icons8-linkedin-50.png

[webIcon]: https://github.com/cgriffs/image_icons/blob/main/IconFolder/socialsicons/icons8-website-50.png

## My Projects
### [Project 1 - PWM Heater Control](https://github.com/brandenjvoss/PWM_heater_control) *(C++ and Arduino)*
This program uses PWM to control output from resistive heaters and uses a DS18B20 digital temperature sensor. The intent is to hold an ambient temperature of 60 degrees celcius inside a box used for fuse testing. The heater_output function will provide full heat up to a sensor reading of 55 degrees celsius. Then, the heater will turn off until a reading of 58 is seen (heater continues to radiate heat even when off raising the temp a few degrees more). Output is then modulated to 50% duty cycle from 58-59 and 38% from 59-60. Again, an output of 0 is acheived when the sensor reads higher than 60 degrees celsius. From here, the temperature will fluctuate from 59.31-60.25 degrees celsius and is successfully maintained.
### [Project 2 - Music Reactive LED Strip](https://github.com/brandenjvoss/music_reactive_LED_strip) *(C++ and Arduino)*
Designed and programmed a PCB for an LED system that responds to audio input.
### [Project 3 - An Improved Machine Learning Model to Detect Static Eccentricity in Induction Motors](https://github.com/brandenjvoss/Electric_motor_fault_detection) *(MATLAB)*
In this work a machine learning model to detect static eccentricity fault in three phase induction motors is presented. The proposed method utilizes the k-nearest neighbour algorithm to classify static eccentricity from healthy operating condition. The biggest advantage of the scheme is that it uses line voltage signals in time domain to perform fault diagnosis. Moreover, only two features, kurtosis and root of sum of squares, are needed to perform the classification. Furthermore, the proposed method is capable of classifying static eccentricity fault independent of load level, fault severity and machine parameters such as stator slot, rotor bar combinations. Experimental data acquired from a 3-phase, 45-bar squirrel cage induction motor has been used to train and test the machine learning model.
### [Project 4 - Alarm Clock](https://github.com/brandenjvoss/alarm_clock) *(C++ and Arduino)*
For this project, I designed an alarm clock and implemented it into a PCB layout. The alarm clock operates off of an Arduino Uno microcontroller and is capable of the following;
  1.	Displays time in 24-hour format on 7-segment LED’s
  2.	Allows time to be set or changed as desired
  3.	Allows alarm time to be set or disabled as desired
  4.	Triggers alarm based on set time
  5.	Brightness of LED display adjusts according to ambient light
  6.	Snooze feature for alarm operation
