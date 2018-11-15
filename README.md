# NUS GET1033 Project: Autonomous Car Washing System 

<p align="center">
Jonathan Mohan (A0168550B) | Chua Hong Huei (A0168608U)
</p>


# Overview


 
**Ever wanted to get a car wash done quickly without the need to wait for an attendant?**
 Look no further as we will be designing an Autonomous Car Washing System to replace the current systems available at petrol kiosks island wide. 
 The system would automatically detect the arrival of a car and would proceed to go through a set of automatic procedures to wash the car when it is in the washing bay area, while informing the others car to wait outside using the signal system at the front of the washing bay. 
 Our project’s aim is to reduce manpower and labour cost, while seeking to improve the efficiency during peak periods.
 
# Components required
- 	5 LED Light Module 
-  1 Proximity Sensor
- 	3 Servo Motors 
- 	Emergency Push Button 
- 	Reset Push Button

![arduino uno](https://user-images.githubusercontent.com/44767760/48461088-e855f880-e80c-11e8-9cec-930c8d258056.jpg)
![jumper cables](https://user-images.githubusercontent.com/44767760/48461089-e8ee8f00-e80c-11e8-9bb7-7dea8eb498f3.jpg)
![led](https://user-images.githubusercontent.com/44767760/48461090-e8ee8f00-e80c-11e8-898f-44a54e291138.jpg)
![proximity sensor](https://user-images.githubusercontent.com/44767760/48461091-e8ee8f00-e80c-11e8-8cba-427322c18e50.jpg)
![push button](https://user-images.githubusercontent.com/44767760/48461092-e9872580-e80c-11e8-96a7-87876423b522.jpg)
![servo motors](https://user-images.githubusercontent.com/44767760/48461093-e9872580-e80c-11e8-9893-f5ca63b36b12.jpg)
 
![full flatlay](https://user-images.githubusercontent.com/44767760/48118023-f0121c00-e2a5-11e8-98ab-381f94fe4555.jpg)


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

7) Both of us did not process strong electronic background


## Application to Module
1)	 Applications mainly linked with **Chatper 7: Physical Computing**

2)	**Conversion of Bits to Atoms**

3) **Physical Computer**: Through the interaction of the Arduino Board with sensors such as the proximity sensors and servo motors. 

4) 	Capabilities of a “Robot”: Our Projects is an apt depiction of what a robot is able to do, namely, think, sense and act. This can be seen from the sensor’s ability to sense/detect the presence of a car and completing a set of rules to direct the car into the washing bay before washing the car 

5) 	**Visual Rhetoric: This can be seen using different LEDs to indicate to the driver the current occupancy of the car washing area + whether the washing procedure is complete.**

6) 	Application to **Janet Murray’s 4 Affordances of Digital Media** 

- **Participatory**: "LOW"
- **Spatial**: "MEDIUM"
- **Encyclopaedic**: "LOW" 
- **Procedural**: ""HIGH""

![digital media affordances](https://user-images.githubusercontent.com/44767760/48494118-23d1e080-e868-11e8-8201-3b4a7b19c496.jpg)


## Video Documentation - Initial 
 
[![](http://img.youtube.com/vi/AXmwF08m7TU/0.jpg)](http://www.youtube.com/watch?v=AXmwF08m7TU "NUS GET Project Documentation Trial 1")

## Video Documentation - Final 
 
*Insert Video*

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

# Indivdual Reflection Chua Hong Huei(A0168608U)

**1.	Overview of Project**
The idea of this project came up during the week Physical Computing was taught. The idea of physical computing was to create an interactive system that is able to sense and respond to the physical world with the help of software and hardware. We were also shown a video whereby water droplets were being moved in different directions controlled by the user. From this, we decided to think of an idea that involves water using bits. As a driver, I have been to car wash and spent a considerable amount of time waiting for the service staff to wash cars in front of me.  Therefore, we came up with the idea of an autonomous car washing system. 

To achieve this idea, we had to use Arduino and several sensors, servo motors and LEDs. Arduino is a popular open source physical computing method consisting of a microcontroller board, sensors and a language which is used for the board’s programming. Using Proximity Sensor and LEDs, the car washing system is able to automatically detect the arrival of a car and guide the driver into the washing bay after which it will go through a set of timed procedures programmed to wash, soap, scrub the car. We have also introduced an emergency stop and start button to ensure the safety of the consumers in the event of a malfunction.

The main objective of this project was to improve washing efficiency using technology available in the market, while at the same time reducing labour and manpower cost. Through this project we can explore the boundaries of what we can really achieve without prior knowledge of coding and constructions of systems.

**2.	How does our project connect to ideas you have learned in this module?**

Our project uses mainly concepts that were taught in week 7 namely “Physical Computing”, “Conversion of Bits to Atoms” and the “Sense-Think-Act” robot.
The concept of Physical Computing is evident in our project as we managed to build an interactive car washing system using hardware and software such as Proximity Sensor, Servo Motors and Arduino that is capable of sensing and responding to actual cars in the world. Also, to ensure that the car is washed, the concept of converting bits to atoms is seen. The car washing system is able to detect the car from a distance and slowly direct it to a stop before activating the Servo Motors which are representing the activation of water, soap and scrubbers in the system.
Furthermore, we were taught that a robot should be able to do 3 things such as sense, think and act which is what our project is capable of. It is first able to sense/detect the presence of a car after which following a set of codes/rules to direct the car into the washing bay before washing the car as a form of act.
Another element that was covered in the lectures was Visual Rhetoric. We applied this in our project by using different coloured LEDs to direct drivers in and out of our car washing system and also inform drivers of the current occupancy of the system.

**3. Analyze the affordances of digital media it uses**

**Participatory- LOW**
(	Does not require much participating from the users as the program functions based on the proximity sensor distance reading
Only require input for Emergency Stop and Start Button from the staff)

**Spatial- MEDIUM**
(Takes in data from the proximity sensor based on the pulse sent out)

**Encyclopedic- LOW**
(Interaction through the code
Unable to store much data as it only uses proximity sensor as an input)

**Procedural- HIGH**
(Must follow a set of rules that is predetermined by our coding, or else the car washing operation would not be able to function efficiently)

**4.	How does it make use of the new abilities of computers?**

Computers have the ability of naming things, repeating steps, making decisions, and manipulating data. Our car washing system is essentially a robot that helps to wash cars. This robot is able to sense data from the proximity sensor and manipulate the codes which is evident in the codes. Initially, we called “WashStartTime = -1” but was eventually manipulated to “WashStartTime = millis()” using the “if” function. “millis()” is a function that acts as a timer which is essentially the same as storing data.
To add on, we intentionally programmed the car washing system to be able to reset itself after every wash by changing the values of variables such as “WashStartTime” and “WaterTime” back to their original values and adding a delay to ensure that the car has sufficient time to exit the washing bay. Once the delay is over, the system would’ve automatically restarted itself and is ready to repeat the same steps to wash another car.
From this, our project is able to combine the abilities of computer to achieve its goal of washing cars automatically.

**5.	How does it build off other projects you have seen?**

Our project is an upgrade to existing car washing systems. Currently, car washing systems are either running fully on manpower or semi. Car washing systems that are running entirely on manpower labour are inefficient as it takes a longer time to wash bigger cars while incurring addition manpower cost. Car washing systems that are not running fully on manpower labour still requires a staff to direct cars into the washing bay, start and stop the washing process.
Through the use of proximity sensors and LEDs, we are able to make car wash fully automatic by eliminating the need for an additional staff on the ground to direct, start and stop the washing process. Thus, increasing the efficiency of car washes and reducing labour and manpower cost.
 

**6.	Challenges I faced throughout the project**

With little to no experience on Arduino, coding and electronics, I faced many challenges during the coding and testing phase of the project. Having no background on the related topics meant that I had to spend time reading sample codes online to understand what the purpose of each line was. To make things worse, we had components such as Proximity Sensors, Servo Motors, Push Button and LEDs that had to be incorporated in the program.
I faced many challenges throughout the coding phase of the project. I was unable to understand codes and unsure of why things were not going right. For a start, I was using “delay” function and “for” loop function to get the servo spinning properly. However, this became a problem when I had to introduce an emergency stop switch. As the delay function in Arduino essentially stops the program from running, my emergency stop will also be either delayed or not registered which poses as a huge problem. After consultation with Dennis, I was advised to not use “for” loop to move the servo so that the emergency stop can be registered during the movement of the servos. 
Without knowing anything about Arduino boards, I had to go around asking what the pin does. For example, there are analog and digital pins that are essentially the same, but the main difference is the analog pin ability to read analog sensors. This was something that I did not know, and it slowed down my progress when programming. Furthermore, breadboards were commonly used in conjunction with Arduino boards. However, I was unsure of how to connect the wires and components such that it was linked resulting in time spent researching and watching videos that explained the connection behind breadboards. For example, we had to run test every time there was a change in the codes that affected the motors. However, we were unsure if it was the code or the connection between the Arduino board and component was wrong. Another example would be the push button. We did not know that there was a way connect it until Dennis instructed us to use a voltmeter to test and find the correct orientation.
 

**Module (General):**

**1.	What have I learnt from the module** 

Through this module, I learnt about the history of computers and am better able to understand the applications of computational is in our everyday lives. From this module, it is interesting to see how things that were taught in lectures were evident in our everyday lives. For example, the concept of procedural rhetoric. Most of times, we often just play games for the sake of entertainment. But through the lecture on Video Games, I learnt that a game can stimulate and change the way we think. For example, the game pong that we made during tutorial. To win, we must try and hit the ball along the edges of our racket to increase the speed of the ball and make it seem unpredictable for the computer to follow. This information is neither given nor told to the player, but it is conveyed via the gameplay. This made me realise that information can be transmitted through games and it is a viable option to use when it comes to educating young kids.
Another takeaway from this module would be the ability to code and understand codes better. At the start of the module, we were tasked to edit a game and include 2 different inputs such as touch, mouse, keyboard, voice and camera. Initially, it was tough as I had no background in computing and it was one of the first few tasks. However, Dennis was very patient and able to teach me how each individual function work and what it does. Also, the website’s ability to inform me of any error allowed me to slowly experiment and learn from my mistakes and understand the functions better. Eventually, I was able to edit the game by removing the voice input and inserting 2 different input namely keyboard and mouse input. Fast forward to the end of the semester, I was in charge of the coding portion of the project and had more opportunities to learn from my mistakes. 

**2.	What did I wish I could have added into my project to enhance its capabilities?**

The concept of “Written Rhetoric” would be one addition that could possibly enhance the capability. Having a screen that direct the drivers and also inform the drivers which process (eg. Washing or Scrubbing) of the car wash they are in. It can also display areas of the car being cleaned to give the drivers a sense of assurance that their car is being washed properly.
Another additional concept would be Virtual Reality. By entering the washing bay, cars can be seen as entering a virtual realm that helps to wash cars. This would act as an experience and entertainment for the drivers while they are waiting for their cars to be washed.

**3.	Application as an Engineer**

From this module, it is evident that computational can applied in many fields including Engineering. For instance, the use of Augmented Reality (Feature Tracking) and Virtual Reality can be used to help engineers display finished products to their customers. Another technology would be digital fabrication which is already in place. Engineers are now using 3D printers and CNC mills to fabricate and print prototypes. 


