# NUS GET1033 Project: Autonomous Car Washing System 

<p align="center">
Jonathan Mohan | Chua Hong Huei
</p>
 
# Overview
 **Ever wanted to get a car wash done quickly without the need to wait for an attendant?**
 Look no further as we will be designing an Autonomous Car Washing System to replace the current systems available at petrol kiosks island wide. 
 The system would automatically detect the arrival of a car and would proceed to go through a set of automatic procedures to wash the car when it is in the washing bay area. 
 Our project’s aim is to reduce manpower and labour cost, while seeking to improve the efficiency during peak periods 
 
# Sensors required
- 	3 LED Light Module 
-  1 Proximity Sensor
- 	3 Servo Motors 
- 	Emergency Push Button 
- 	Reset Push Button

# Proposed Timeline
•	**Week 8-9**: Consolidate on the current plan and ensure that the entire process is feasible. Find out about the sensors available for students to use in the project. Read up on Arduino programming and start working on the code. 

• **Week 10**: Complete the coding process, ensure that there are no errors in the code (flow).  At the same time start working on the mock up prototype we will need for the physical demonstration

•	**Week 11-12**: Collect data required for individual sensors through testing out the code using a working prototype. Calibrate the code to ensure it is fully functional. Work on our project documentation for the final presentation using github.com

•	**Week 13**: Minor fine tuning, before the actual presentation. Coding Complete, step by step workflow process complete, reflections complete. Prototype completed for presentation

# Process Flow Chart
![get flow chart](https://user-images.githubusercontent.com/44767760/47988272-c5e12280-e11c-11e8-86c4-449abc26c551.jpg)

# Operation

1)	The car would be directed into the washing bay, through an indication via the green LED light module. The front proximity sensors would ensure that the car is completely in the washing bay. The 3 LED Light Module would guide the driver on the distance to the designated washing bay based on the front proximity sensor.
Green LED: Drive In
Orange LED: Slow Down
Red LED: Stop

 ![process 1](https://user-images.githubusercontent.com/44767760/47995260-aa334780-e12f-11e8-92da-e02691e2b0eb.jpg)

2)	Once the proximity sensors are activated (meaning that the car is at the designated spot), the LED would turn red and the washing process would begin automatically.

3)	**Car Wash Process: Water (30secs) -> Soap (30secs) -> Scrubbing (30secs) -> Water (30secs)** 

**Water Hose** -> First servo motor will activate for 30 seconds to simulate washing 

 ![final process - water to soap](https://user-images.githubusercontent.com/44767760/47995215-81ab4d80-e12f-11e8-8aeb-aa1915f50185.jpg)

**Soap** -> Second servo motor will be activated for 30 seconds once the washing simulation is complete.

 ![final process - soap to scrub](https://user-images.githubusercontent.com/44767760/47995213-8112b700-e12f-11e8-9b64-f60c49ab8d06.jpg)

**Scrubbing** -> Third servo motor would be used to simulate scrubbing action. It will run for 30 seconds. 

 ![final process - scrub to water](https://user-images.githubusercontent.com/44767760/47995210-8112b700-e12f-11e8-88b3-390b8c68ee70.jpg)

**Water Hose** -> Process will end off with 30 seconds simulated wash

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

## Video Documentation

Our Project Documentation Video can be seen from  [GET Project Documentation](https://www.youtube.com/watch?v=AXmwF08m7TU&feature=youtu.be).

## Actual Challenges faced

### 1)	The addition of additional servo motors
Initially we intended to only use 2 servo motors to simulate 4 actions, however through the programming and consultation Dennis, we realized that having a separate motor for each process would allow easier troubleshoot in case of problems while providing us a smoother, cleaner flow in the programming code. 
Hence, we decided to use 3 separate servo motors to indicate the different processes (Water, Soap, Scrubbing)

   ![servo](https://user-images.githubusercontent.com/44767760/48037758-ce7f3a80-e1a8-11e8-9cf8-6476d9cdb451.jpg)
 
### 2)	LED not working properly 
We faced several issues with the LED whereby it did not light up whenever it was programmed to and at times the it was lit up dimly. We had to go back to our program to fix the mistakes to ensure that the LED and proximity sensors work together through several troubleshoots. For the dim LED, we tested several other LEDs to ensure that it was not a circuit set-up problem. 

### 3)	Getting the timing right for the servo motor rotations and ensuring that it flows smoothly with all the other processes
We had many problems programming the servo motors to move continually and consecutively and had to adjust our program several times to fix the issue. It was through reading up online / videos that we realized that there’s a certain way servo motors are programmed to work, and we modified our program as seen below in the picture to rectify it. 
 
   ![coding comparison](https://user-images.githubusercontent.com/44767760/48037826-0ab29b00-e1a9-11e8-94ad-a68fc4b47c8b.jpg)
 
### 4)	Proximity Sensor Issues (Hardware)
Initially we could not figure out why our proximity sensor was not working properly though the programming was correct. We soon realized that it was because the echo and trigger pin were connected incorrectly and rectified it. 

   ![arduino connection](https://user-images.githubusercontent.com/44767760/48037825-0a1a0480-e1a9-11e8-8bd8-080000a92c57.jpg)
 
### 5)	Proximity sensor measurement was inaccurate (Software)
During the construction of the hardware, we realized that the proximity sensor values fluctuate very often when any object is placed near the sensor. Furthermore, we realized that the sensor only works after a certain distance based on the experiments we did (>5mm). Hence, we decided to give a range for the different distances (<10cm Red Colour to indicate car stop, (10-15cm) Orange LED light up to indicate car to slow down, 15cm onwards Red LED light up to instead of using a fix number. This is to provide further accurate and room for error in this automatous system.

  ![proximity sensor settings](https://user-images.githubusercontent.com/44767760/48037792-e9ea4580-e1a8-11e8-9dce-df97283918c8.jpg)
 
In addition, the calibration of the Proximity Sensor also posed us several problems.  The sensor would require a certain amount of time  during start up, resulting in the activation of the washing system. Therefore, we added the code as shown below. This is to ensure       that the proximity sensor is being calibrated during the start up of the entire program before any vehicle enters the washing bay.

  ![proximity sensor calibration](https://user-images.githubusercontent.com/44767760/48037853-261da600-e1a9-11e8-8598-acd4822447a0.jpg)

### 6)	Incorrect rotation of servos 
Initially our servo was not working properly (instead of moving at an angle it was moving continuously acting like a normal motor). However, we soon realized it was due to our program instead of the hardware itself and used the for function to ensure the motor rotated correctly. 

   ![servo motor rotation](https://user-images.githubusercontent.com/44767760/48037868-2fa70e00-e1a9-11e8-8efd-e16bb9444eec.jpg)
 
### 7)	Accumulations of Delays in the entire project
The accumulation of delays meant that the motors and LED timings would not tally and work together. Furthermore, the emergency push button was unable to work efficiency with the delays put in place. However, once we change the program to allow continuous rotations (as seen in point 4), the emergency button was able to trigger the entire system to come to a halt. 

### 8)	Both washing operations in Stage 1 and Stage 4 clashes
By adding the photo below, we ensured that the washing operation in stage 4 will only be activated when WashStartTime = -1 (Initial condition) when it’s not in use. This ensures that the 2 process will not clash. Initially, the servo was already activated in stage 1, and would disable the washing operation, resulting in servo motor having a “jerky” reaction. 


## Final Code (With Explanations) 

![code p1](https://user-images.githubusercontent.com/44767760/48067931-7548f280-e20c-11e8-9199-2c900d5904a7.png)
![code p3](https://user-images.githubusercontent.com/44767760/48067934-7548f280-e20c-11e8-94d7-8d6d6e9f6ec3.png)
![code p4](https://user-images.githubusercontent.com/44767760/48067935-75e18900-e20c-11e8-8f30-5dd3a6517fb7.png)
![code p5](https://user-images.githubusercontent.com/44767760/48067937-767a1f80-e20c-11e8-8c9d-483e81fa7c95.png)
![code p6](https://user-images.githubusercontent.com/44767760/48067938-767a1f80-e20c-11e8-9c65-6066e51e0cbc.png)
![code p7](https://user-images.githubusercontent.com/44767760/48067939-767a1f80-e20c-11e8-9171-1dbf8e03f6b0.png)
![code p8](https://user-images.githubusercontent.com/44767760/48067940-7712b600-e20c-11e8-9cfa-bc04f13637ad.png)
![code p9](https://user-images.githubusercontent.com/44767760/48067942-77ab4c80-e20c-11e8-9900-097ec898a157.png)
![code p2](https://user-images.githubusercontent.com/44767760/48067932-7548f280-e20c-11e8-8f3f-bc1e0f9b389c.png)

Full Program Code is available to download : [GET Coding.docx](https://github.com/jm24travelz/GET/files/2553369/GET.Coding.docx)

