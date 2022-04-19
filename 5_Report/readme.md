# AIM
* THIS PROJECT HELPS IN DETECTING THE OBSTACLES ON THE FRONT OF THE PERSON & USED TO DETECT OBJECT IN DARK AREAS 
# INTRODUCTION
* HC-SR-04 ULTRASONIC MODULE


In ultrasonic module HCSR04, we have to give trigger pulse, so that it will generate ultrasound of frequency 40 kHz. After generating ultrasound i.e. 8 pulses of 40 kHz, it makes echo pin high. Echo pin remains high until it does not get the echo sound back. So the width of echo pin will be the time for sound to travel to the object and return back. Once we get the time we can calculate distance, as we know the speed of sound.
* HC-SR04 can measure up to range from 2 cm - 400 cm.
* HC-SR04 PIN DESCRIPTION
* VCC - +5 V supply
* TRIG – Trigger input of sensor. Microcontroller applies 10 us trigger pulse to the HC-SR04 ultrasonic module.
* ECHO–Echo output of sensor. Microcontroller reads/monitors this pin to detect the obstacle or to find the distance.
* GND – Ground

# COMPONENTS
* AtMega328p
* HC-SR-04 ULTRASONIC SENSOR
* BUZZERS
* LED
* VOLTAGE SUPPLY

# USES
* IT HELPS IN DETECTING THE OBSTACLES
* IT HELPS TO RECOGNIZE THE OBSTACLES IN FRONT THROUGH BUZZER
