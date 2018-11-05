# GET1033 Project: Autonomous Car Washing System 

 # Jonathan Mohan | Chua Hong Huei
 
 ##Overview
 Overview: Ever wanted to get a car wash done quickly without the need to wait for an attendant? 
 Look no further as we will be designing an Autonomous Car Washing System to replace the current systems available at petrol kiosks island wide. 
 The system would automatically detect the arrival of a car and would proceed to go through a set of automatic procedures to wash the car when it is in the washing bay area. 
 Our project’s aim is to reduce manpower and labour cost, while seeking to improve the efficiency during peak periods 
 
 ## Sensors required
1.	3 LED Light Module 
2.	1 Proximity Sensor
3.	3 Servo Motors 
4.	Emergency Push Button 
5.	Reset Push Button


## How it works
1. Once a car enters the washing bay, the TV would display an indication for the driver to inform suitable parking spot (center of the washing bay)
2. Upon entering the center, the car would have to fully come to a halt, activating the weight and motion sensor, closing the door in the process
3. The activation of both sensors would automatically turn on the washing process
4. Car wash process : Water (30secs) -> Soap (30secs) -> Scrubbing (2 revs) -> Water (30secs) -> Dryer (1min)
Timing of each washing cycle is dependent on the size of the car (determined by the weight sensors)
5. In case of an emergency or malfunction, an attendant will be notified and would halt the system via the emergency button (touch sensor). If not, the driver can sound his horn, stopping the washing system (sound sensor)
6. Once the washing process is completed (laster moisture sensor), the dryer would be activated
7. After the drying process is completed, a green light would appear, opening the door, allowing the driver to drive off
