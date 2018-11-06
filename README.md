# GET1033 Project: Autonomous Car Washing System 

# Jonathan Mohan | Chua Hong Huei
 
# Overview
 Ever wanted to get a car wash done quickly without the need to wait for an attendant? 
 Look no further as we will be designing an Autonomous Car Washing System to replace the current systems available at petrol kiosks island wide. 
 The system would automatically detect the arrival of a car and would proceed to go through a set of automatic procedures to wash the car when it is in the washing bay area. 
 Our project’s aim is to reduce manpower and labour cost, while seeking to improve the efficiency during peak periods 
 
# Sensors required
1.	3 LED Light Module 
2.	1 Proximity Sensor
3.	3 Servo Motors 
4.	Emergency Push Button 
5.	Reset Push Button

# Proposed Timeline
•	Week 8-9: Consolidate on the current plan and ensure that the entire process is feasible. Find out about the sensors available for students to use in the project. Read up on Arduino programming and start working on the code. 

• Week 10: Complete the coding process, ensure that there are no errors in the code (flow).  At the same time start working on the mock up prototype we will need for the physical demonstration

•	Week 11-12: Collect data required for individual sensors through testing out the code using a working prototype. Calibrate the code to ensure it is fully functional. Work on our project documentation for the final presentation using github.com

•	Week 13: Minor fine tuning, before the actual presentation. Coding Complete, step by step workflow process complete, reflections complete. Prototype completed for presentation

# Process Flow Chart
![get flow chart](https://user-images.githubusercontent.com/44767760/47988272-c5e12280-e11c-11e8-86c4-449abc26c551.jpg)

# Operation

1)	The car would be directed into the washing bay, through an indication via the green LED light module. The front proximity sensors would ensure that the car is completely in the washing bay. The 3 LED Light Module would guide the driver on the distance to the designated washing bay based on the front proximity sensor.
Green LED: Drive In
Orange LED: Slow Down
Red LED: Stop

 ![process 1](https://user-images.githubusercontent.com/44767760/47995260-aa334780-e12f-11e8-92da-e02691e2b0eb.jpg)

2)	Once the proximity sensors are activated (meaning that the car is at the designated spot), the LED would turn red and the washing process would begin automatically.

3)	Car Wash Process: Water (30secs) -> Soap (30secs) -> Scrubbing (30secs) -> Water (30secs) 

Water Hose -> First servo motor will activate for 30 seconds to simulate washing 

 ![final process - water to soap](https://user-images.githubusercontent.com/44767760/47995215-81ab4d80-e12f-11e8-8aeb-aa1915f50185.jpg)

Soap -> Second servo motor will be activated for 30 seconds once the washing simulation is complete.

 ![final process - soap to scrub](https://user-images.githubusercontent.com/44767760/47995213-8112b700-e12f-11e8-9b64-f60c49ab8d06.jpg)

Scrubbing -> Third servo motor would be used to simulate scrubbing action. It will run for 30 seconds. 

 ![final process - scrub to water](https://user-images.githubusercontent.com/44767760/47995210-8112b700-e12f-11e8-88b3-390b8c68ee70.jpg)

Water Hose -> Process will end off with 30 seconds simulated wash

 ![final process - scrub to water](https://user-images.githubusercontent.com/44767760/47995210-8112b700-e12f-11e8-88b3-390b8c68ee70.jpg)

4)	Once the process is completed, the red LED would revert to green, signalling to the driver that the process is complete, indicating that the driver is free to move out of the washing bay.  (End of Process)

 ![final process - drive out](https://user-images.githubusercontent.com/44767760/47995207-807a2080-e12f-11e8-906d-73a640110e65.jpg)

5)	An emergency push button would be situated along the washing bay to ensure ease of access in any situation whereby the automatic washing process runs into any problems. Once the button is pressed, the process would come to a halt, and a technician would come down to check on the situation. An additional push button would be in place to reset the whole system. 

 ![final process - emergency stop](https://user-images.githubusercontent.com/44767760/47995208-807a2080-e12f-11e8-9044-6a37e1a79028.jpg)

## Potential Challenges (Prior to the Start of Project) 
1)	With little to no coding and programming background, this project will be an interesting challenge for us to see whether we are able to complete the coding 
2)	Unsure of the availability of certain specific sensors in school, such as the proximity sensor
3)	Usage of proximity sensors would be very tricky as they are very sensitive sensors, this would require multiple test runs to ensure that we get the correct range for the front readings
4)	Setting up of Arudino Circuit Board without much prior experience
5)	Construction of the Autonomous Washing Bay prototype to simulate the washing, soaping, scrubbing process 
6)	Time management in terms of completing the project before the dateline including the proper documentation
7)	Both of us did not process strong electronic background






