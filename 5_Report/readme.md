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
---------------------------------------------------------------------------------------------------------------------
# High  level requirments
![HL](https://user-images.githubusercontent.com/101693748/164510426-b39f941e-9113-4a60-89fe-bc6a7f26833b.png)
# Low level requirments
![LL](https://user-images.githubusercontent.com/101693748/164510683-c055f0a0-0414-48f3-87ad-4c2d2f004bd3.png)
--------------------------------------------------------------------------------------------------------------------
# Diagrams
# BLOCK DIAGRAM
![BLOCK DIAGRAM](https://user-images.githubusercontent.com/101693748/164351693-c696de79-bd6a-4c1b-a3a3-528ea33c0ae5.png)
# FLOW CHART
![flowchart](https://user-images.githubusercontent.com/101693748/164351761-1eed76fe-e105-4c38-ae03-a14313b126e3.png)
# STATE TRASNSION DIAGRAM
![state transion diagram](https://user-images.githubusercontent.com/101693748/164351831-9a6d7f56-999c-43d0-8da3-6041a32f5b94.png)
# DATA FLOW TRANSION
![DATA FLOW](https://user-images.githubusercontent.com/101693748/164353044-e4383b4d-51d2-41aa-a054-f7c6ae6ea751.png)
# SCHEMATIC DIAGRAM
![CIRCUIT](https://user-images.githubusercontent.com/101693748/164353082-6f033582-2362-4563-90d6-48dd0cf7b3f1.png)
# output
# @ off condition
![OF](https://user-images.githubusercontent.com/101693748/164054453-2c518578-3da9-4c48-aeb8-c54af68b0c85.png)
# @ on condition
![CIRCUIT](https://user-images.githubusercontent.com/101693748/164054571-9741bf62-4b37-4b08-8198-7add3db3e9df.png)

# USES
* IT HELPS IN DETECTING THE OBSTACLES
* IT HELPS TO RECOGNIZE THE OBSTACLES IN FRONT THROUGH BUZZER
---------------------------------------------------------------------------------------------------
# 4W & H   (WHO,WHAT,WHEN,WHERE,HOW)
---------------------------------------------------------------------------------------------------
# *WHO
* SMART DETECTOR IS THE APPLICATION USED TO DETECT OBJECTIVES IN FRONT OF IT AND IS USED FOR BLIND PERSON OR EYE ISSUERS
# *WHAT
*  IT IS CONVIENT AND EASY TO USE
# *WHEN
* IT CAN BE USED BY ANYONE IN ANY TIME MOSTLY  
# *WHERE
* IT CAN BE USED NEARBY U OR TO SOME ANOTHER PLACES
# *HOW 
* IT IS EASY TO OPERATE BY WHICH AN ORDIRAY MAN CAN OPERATE IT EASILY AND IT GIVES THE RESULTS TOO EASY

-----------------------------------------------------------------------------------------------------
# * SWOT(STRENGTH,WEAKNESS,OPPORTUNITY,THREATS)
-----------------------------------------------------------------------------------------------------
# *STRENGTH
* HELPS BLIND PEOPLE TO WALK EASILY TO DESTINATION
* HELPS BLIND PEOPLE FOR OBSTACLES DETECTION
* ALERT THEM FOR DIG 
* AUTODETECTION HELPS IN ALARMING
* SIMPLE AND LOW COST
# * WEAKNESS
* LIMITED
* GPS TRACKING CAN BE DECTECTED UPTO 40M
* LITTLE SENSOR SUPPORT
# * OPPORTUNITY
* GPS TRACK TO EXTEND
* IOT 
* LCD DISPLAY
# * THREATS
* POWER CONSUMPTION
* SENSOR DISCONNECTS
* FAIL OF COMPONENTS
