## HIGH LEVEL REQUIREMENTS
|**ID**|**Requirements**|**Description**|**Status**|
| :- | :- | :- | :- |
| HLR1 | Wiper Control module | When moisture sensor senses the water, it sends signal to wiper shield to turn on | Implemented |
| HLR2 | Interior light control using PIR sensor | Adjustment of interior lighting using PIR Motion Detection Sensor (when door is opened i.e. when motion is detected, the interior lighting will work) | Implemented |
| HLR3 | Adaptive light Control System using LDR | LDR sensor sense the presence and absence of light is necessary | Implemented |
| HLR4 | Car Reverse Gear Buzzer | Car Reverse Radar Sensor detect the objects during reversing the vehicle and sends signal to buzzer | Implemented |



## LOW LEVEL REQUIREMENTS
|**ID**|**Requirements**|**Description**|**Status**|
| :- | :- | :- | :- |
| HLR1-LLR1 | When moisture sensor detects the water content wiper shields starts working | GPIO pin PD12 is set and the LED on the discovery board glows | Implemented |
| HLR1-LLR2 | When no water is detected from moisture sensor wiper shields will not work | GPIO pin PD12 is reset and the LED on the discovery board turned off | Implemented |
| HLR2-LLR1 | When the door is opened motion is detected, interior lighting will work properly | GPIO pin PD12 is set and the LED on the discovery board glows | Implemented |
| HLR2-LLR2 | When the door is closed motion is not detected interior lighting will not work | GPIO pin PD12 is reset and the LED on the discovery board turned off | Implemented |
| HLR3-LLR1 | When the darkness is detected around the exterior lights will work properly.| GPIO pin PD12 is set and the LED on the discovery board glows | Implemented |
| HLR3-LLR2 | When the high intensity lights are detected around exterior lights will not work | GPIO pin PD12 is reset and the LED on the discovery board turned off | Implemented |
| HLR4-LLR1 | When the person in a vehicle uses reverse gear the buzzer starts beeping | GPIO pin PD12 is set and the LED on the discovery board glows | Implemented |
| HLR4-LLR2 | When the reverse gear is not in use the buzzer will not work | GPIO pin PD12 is reset and the LED on the discovery board turned off | Implemented |
