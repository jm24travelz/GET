# NUS GET1033 Project: Autonomous Car Washing System 

<p align="center">
Jonathan Mohan (A0168550B) | Chua Hong Huei (A0168608U)
</p>

![final documentation](https://user-images.githubusercontent.com/44767760/48536489-b5356700-e8e9-11e8-92a0-92db50883985.jpg)


# Overview


 
<p align="justify">**Ever wanted to get a car wash done quickly without the need to wait for an attendant?**
 Look no further as we will be designing an Autonomous Car Washing System to replace the current systems available at petrol kiosks island wide. 
 The system would automatically detect the arrival of a car and would proceed to go through a set of automatic procedures to wash the car when it is in the washing bay area, while informing the cars to wait outside using our signal system outside the washing bay. 
 Our project’s aim is to reduce manpower and labour cost, while seeking to improve the efficiency during peak periods.</p>
 
# Components required
- 	5 LED Light Module 
-  1 Proximity Sensor
- 	3 Servo Motors 
- 	Emergency Start/Stop Push Button

![arduino uno](https://user-images.githubusercontent.com/44767760/48461088-e855f880-e80c-11e8-9cec-930c8d258056.jpg)
![jumper cables](https://user-images.githubusercontent.com/44767760/48461089-e8ee8f00-e80c-11e8-9bb7-7dea8eb498f3.jpg)
![led](https://user-images.githubusercontent.com/44767760/48461090-e8ee8f00-e80c-11e8-898f-44a54e291138.jpg)
![proximity sensor](https://user-images.githubusercontent.com/44767760/48461091-e8ee8f00-e80c-11e8-8cba-427322c18e50.jpg)
![push button](https://user-images.githubusercontent.com/44767760/48461092-e9872580-e80c-11e8-96a7-87876423b522.jpg)
![servo motors](https://user-images.githubusercontent.com/44767760/48461093-e9872580-e80c-11e8-9893-f5ca63b36b12.jpg)
 
![full flatlay](https://user-images.githubusercontent.com/44767760/48538321-17dd3180-e8ef-11e8-821e-4409955495b5.jpg)


# Proposed Timeline
•	**Week 8-9**: Consolidate on the current plan and ensure that the entire process is feasible. Find out about the sensors available for students to use in the project. Read up on Arduino programming and start working on the code. 

• **Week 10**: Complete the coding process, ensure that there are no errors in the code (flow).  At the same time start working on the mock up prototype we will need for the physical demonstration

•	**Week 11-12**: Collect data required for individual sensors through testing out the code using a working prototype. Calibrate the code to ensure it is fully functional. Work on our project documentation for the final presentation using github.com

•	**Week 13**: Minor fine tuning, before the actual presentation. Coding Complete, step by step workflow process complete, reflections complete. Prototype completed for presentation.

# Process Flow Chart
![get flow chart](https://user-images.githubusercontent.com/44767760/48535654-055efa00-e8e7-11e8-8129-7cd077ae788e.jpg)

# Operation

The car would be directed into the washing bay, through an indication via the green LED light module. The front proximity sensors would ensure that the car is completely in the washing bay. The 3 LED Light Module would guide the driver on the distance to the designated washing bay based on the front proximity sensor.

Green LED: Drive In

Orange LED: Slow Down

Red LED: Stop

 ![process 1](https://user-images.githubusercontent.com/44767760/47995260-aa334780-e12f-11e8-92da-e02691e2b0eb.jpg)

Once the proximity sensors are activated (meaning that the car is at the designated spot), the LED and the external signal would turn red. Washing process would begin automatically. 

**Car Wash Process: Water (30secs) -> Soap (30secs) -> Scrubbing (30secs) -> Water (30secs)** 

**Water Hose** -> First servo motor will activate for 30 seconds to simulate washing.

 ![final process - water to soap](https://user-images.githubusercontent.com/44767760/47995215-81ab4d80-e12f-11e8-8aeb-aa1915f50185.jpg)

**Soap** -> Second servo motor will be activated for 30 seconds once the washing simulation is complete.

 ![final process - soap to scrub](https://user-images.githubusercontent.com/44767760/47995213-8112b700-e12f-11e8-9b64-f60c49ab8d06.jpg)

**Scrubbing** -> Third servo motor would be used to simulate scrubbing action. It will run for 30 seconds. 

 ![final process - scrub to water](https://user-images.githubusercontent.com/44767760/47995210-8112b700-e12f-11e8-88b3-390b8c68ee70.jpg)

**Water Hose** -> Process will end off with 30 seconds simulated wash

 ![final process - scrub to water](https://user-images.githubusercontent.com/44767760/47995210-8112b700-e12f-11e8-88b3-390b8c68ee70.jpg)

Once the wash is completed, the Green LED will light up inform the driver that the car wash is complete and he can drive the car out of the washing bay. (End of Process)

 ![final process - drive out](https://user-images.githubusercontent.com/44767760/47995207-807a2080-e12f-11e8-906d-73a640110e65.jpg)

An emergency push button would be situated along the washing bay to ensure ease of access in any situation whereby the automatic washing process runs into any problems. Once the button is pressed, the process would come to a halt, and a technician would come down to check on the situation. The same pushbutton would be used to start the system. 

 ![final process - emergency stop](https://user-images.githubusercontent.com/44767760/47995208-807a2080-e12f-11e8-9044-6a37e1a79028.jpg)

## Potential Challenges (Prior to the Start of Project) 
1.With little to no coding and programming background, this project will be an interesting challenge for us to see whether we are able to complete the coding.

2.Unsure of the availability of certain specific sensors in school, such as the proximity sensor.

3.Usage of proximity sensors would be very tricky as they are very sensitive sensors, this would require multiple test runs to ensure that we get the correct range for the front readings.

4.Setting up of Arudino Circuit Board without much prior experience.

5.Construction of the Autonomous Washing Bay prototype to simulate the washing, soaping, scrubbing process.

6.Time management in terms of completing the project before the dateline including proper documentation.

7.Neither of us possessed strong skills and background knowledge related to electronics. 


## Application to Module
1.Applications mainly linked with **Chapter 7: Phyical Computing, Robot.**

2.**Conversion of Bits to Atoms**

3.**Physical Computer**: Through the interaction of the Arduino Board with sensors such as the proximity sensors and servo motors. 

4.Capabilities of a “Robot”: Our Projects is an apt depiction of what a robot is able to do, namely, think, sense and act. This can be seen from the sensor’s ability to sense/detect the presence of a car and completing a set of rules to direct the car into the washing bay before washing the car 

5.**Visual Rhetoric: This can be seen using different LEDs to indicate to the driver the current occupancy of the car washing area + whether the washing procedure is complete.**

6.Application to **Janet Murray’s 4 Affordances of Digital Media** 

- **Participatory**: "LOW"
- **Spatial**: "MEDIUM"
- **Encyclopaedic**: "LOW" 
- **Procedural**: ""HIGH""

![digital media affordances](https://user-images.githubusercontent.com/44767760/48494118-23d1e080-e868-11e8-8201-3b4a7b19c496.jpg)


## Video Documentation - Initial 
 
[![](http://img.youtube.com/vi/AXmwF08m7TU/0.jpg)](http://www.youtube.com/watch?v=AXmwF08m7TU "NUS GET Project Documentation Trial 1")

## Video Documentation - Final 
 
[![](http://img.youtube.com/vi/QXAhWpdfmwc/0.jpg)](https://www.youtube.com/watch?v=QXAhWpdfmwc&feature=youtu.be "Final Project Process Run")

## Actual Challenges: 

**1.Implementation of Multiple Servo Motors**

<p align="justify">Initially we intended to only use 2 servo motors to simulate 4 actions, however through the programming and consultation Dennis, we realized that having a separate motor for each process would allow easier troubleshoot in case of problems while providing us a smoother, cleaner flow in the programming code. 
Hence, we decided to use 3 separate servo motors to indicate the different processes.(Water, Soap, Scrubbing) </p>

   ![servo](https://user-images.githubusercontent.com/44767760/48037758-ce7f3a80-e1a8-11e8-9cf8-6476d9cdb451.jpg)
 
**2.LED malfunctions**

<p align="justify">We faced several issues with the LED whereby it did not light up whenever it was programmed to and at times it was lit up dimly. We had to go back to our program to fix the mistakes to ensure that the LED and proximity sensors work together through several troubleshoots. For the dim LED, we tested several other LEDs to ensure that it was not a circuit set-up problem.</p>

**3.Getting the timing right for the servo motor rotations and ensuring that it flows smoothly with all the other processes**

<p align="justify">We faced many problems programming the servo motors to move continously and consecutively, and had to constantly edit our program to fix the issue. It was through articles and videos online that we found a way to turn our servo motors using if statements (right) instead of the for loop function (left). </p>
 
   ![coding comparison](https://user-images.githubusercontent.com/44767760/48037826-0ab29b00-e1a9-11e8-94ad-a68fc4b47c8b.jpg)
 
**4.Proximity Sensor Issues (Hardware)**

Initially we could not figure out why our proximity sensor was not working properly though the programming was correct. We soon realized that it was because the echo and trigger pin were connected incorrectly and rectified it. 

   ![arduino connection](https://user-images.githubusercontent.com/44767760/48037825-0a1a0480-e1a9-11e8-8bd8-080000a92c57.jpg)
 
**5.Proximity sensor measurement was inaccurate (Software)**

<p align="justify">During the construction of the hardware, we realized that the proximity sensor values fluctuate very often when any object is placed near the sensor. Furthermore, we realized that the sensor only works after a certain distance based on the experiments we did (>5cm). Hence, we decided to give a range for the different distances. </p>

Red: < 10cm

Orange: 10-15cm

Green: > 15cm 

  ![proximity sensor settings](https://user-images.githubusercontent.com/44767760/48037792-e9ea4580-e1a8-11e8-9dce-df97283918c8.jpg)
 
<p align="justify">In addition, the calibration of the Proximity Sensor also posed us several problems.  The sensor would require a certain amount of time  during start up, resulting in the activation of the washing system. Therefore, we added the code as shown below. This ensures that the proximity sensor is being calibrated during the initialisation of the program.</p>

  ![proximity sensor calibration](https://user-images.githubusercontent.com/44767760/48037853-261da600-e1a9-11e8-8598-acd4822447a0.jpg)

**6.Incorrect rotation of servos**

<p align="justify">Initially our servo was not working properly (instead of moving at an angle it was moving continuously acting like a normal motor). However, we soon realized it was due to our program instead of the hardware itself and used the for function to ensure the motor rotated correctly. </p>

   ![servo motor rotation](https://user-images.githubusercontent.com/44767760/48037868-2fa70e00-e1a9-11e8-8efd-e16bb9444eec.jpg)
 
**7.Accumulations of Delays in the entire project**

<p align="justify">The accumulation of delays meant that the motors and LED timings would not tally and work together. Furthermore, the emergency push button was unable to work efficiency with the delays put in place. However, once we change the program to allow continuous rotations (as seen in point 3), the emergency button was able to trigger the entire system to come to a halt. </p>

**8.Both washing operations in Stage 1 and Stage 4 clashes**

As shown in the video below, the servo motor is unable to rotate properly at stage 4 (Final Wash) as it clashes with the codes written for stage 1 (Initial Wash). 

[![](http://img.youtube.com/vi/Tm-8aYyyA2Y/0.jpg)](https://www.youtube.com/watch?v=Tm-8aYyyA2Y&feature=youtu.be "Servo Motor not working")

<p align="justify">By adding the code below, we ensured that the washing operation in stage 4 will only be activated when WashStartTime = -1 (Initial condition) when it’s not in use. This ensures that the 2 process will not clash. Initially, the servo was already activated in stage 1, and would disable the washing operation, resulting in servo motor having a “jerky” reaction. </p>

![servo motor rotation](https://user-images.githubusercontent.com/44767760/48539123-3d6b3a80-e8f1-11e8-9830-e103a05ec725.jpg)


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

# Indivdual Reflection 

### Chua Hong Huei(A0168608U) 

**Project:**

1.&nbsp;Overview of Project

<p align="justify">The idea of this project came up during the week Physical Computing was taught. The idea of physical computing was to create an interactive system that is able to sense and respond to the physical world with the help of software and hardware. We were also shown a video whereby water droplets were being moved in different directions controlled by the user. From this, we decided to think of an idea that involves water using bits. As a driver, I have been to car wash and spent a considerable amount of time waiting for the service staff to wash cars in front of me.  Therefore, we came up with the idea of an autonomous car washing system. </p>

<p align="justify">To achieve this idea, we had to use Arduino and several sensors, servo motors and LEDs. Arduino is a popular open source physical computing method consisting of a microcontroller board, sensors and a language which is used for the board’s programming. Using Proximity Sensor and LEDs, the car washing system is able to automatically detect the arrival of a car and guide the driver into the washing bay after which it will go through a set of timed procedures programmed to wash, soap, scrub the car. We have also introduced an emergency stop and start button to ensure the safety of the consumers in the event of a malfunction. </p>

<p align="justify">The main objective of this project was to improve washing efficiency using technology available in the market, while at the same time reducing labour and manpower cost. Through this project we can explore the boundaries of what we can really achieve without prior knowledge of coding and constructions of systems. </p>

2.&nbsp;How does our project connect to ideas you have learned in this module?

<p align="justify">Our project uses mainly concepts that were taught in week 7 namely “Physical Computing”, “Conversion of Bits to Atoms” and the “Sense-Think-Act” robot.
The concept of Physical Computing is evident in our project as we managed to build an interactive car washing system using hardware and software such as Proximity Sensor, Servo Motors and Arduino that is capable of sensing and responding to actual cars in the world. Also, to ensure that the car is washed, the concept of converting bits to atoms is seen. The car washing system is able to detect the car from a distance and slowly direct it to a stop before activating the Servo Motors which are representing the activation of water, soap and scrubbers in the system. </p>
<p align="justify">Furthermore, we were taught that a robot should be able to do 3 things such as sense, think and act which is what our project is capable of. It is first able to sense/detect the presence of a car after which following a set of codes/rules to direct the car into the washing bay before washing the car as a form of act.
Another element that was covered in the lectures was Visual Rhetoric. We applied this in our project by using different coloured LEDs to direct drivers in and out of our car washing system and also inform drivers of the current occupancy of the system. </p>

3.&nbsp;Analyze the affordances of digital media it uses

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

4.&nbsp;How does it make use of the new abilities of computers?

<p align="justify">Computers have the ability of naming things, repeating steps, making decisions, and manipulating data. Our car washing system is essentially a robot that helps to wash cars. This robot is able to sense data from the proximity sensor and manipulate the codes which is evident in the codes. Initially, we called “WashStartTime = -1” but was eventually manipulated to “WashStartTime = millis()” using the “if” function. “millis()” is a function that acts as a timer which is essentially the same as storing data.</p>
<p align="justify">To add on, we intentionally programmed the car washing system to be able to reset itself after every wash by changing the values of variables such as “WashStartTime” and “WaterTime” back to their original values and adding a delay to ensure that the car has sufficient time to exit the washing bay. Once the delay is over, the system would’ve automatically restarted itself and is ready to repeat the same steps to wash another car. </p>
From this, our project is able to combine the abilities of computer to achieve its goal of washing cars automatically. 

5.&nbsp;How does it build off other projects you have seen?

<p align="justify">Our project is an upgrade to existing car washing systems. Currently, car washing systems are either running fully on manpower or semi. Car washing systems that are running entirely on manpower labour are inefficient as it takes a longer time to wash bigger cars while incurring addition manpower cost. Car washing systems that are not running fully on manpower labour still requires a staff to direct cars into the washing bay, start and stop the washing process.</p>
<p align="justify">Through the use of proximity sensors and LEDs, we are able to make car wash fully automatic by eliminating the need for an additional staff on the ground to direct, start and stop the washing process. Thus, increasing the efficiency of car washes and reducing labour and manpower cost. </p>
 

6.&nbsp;Challenges I faced throughout the project

<p align="justify">With little to no experience on Arduino, coding and electronics, I faced many challenges during the coding and testing phase of the project. Having no background on the related topics meant that I had to spend time reading sample codes online to understand what the purpose of each line was. To make things worse, we had components such as Proximity Sensors, Servo Motors, Push Button and LEDs that had to be incorporated in the program.</p>
<p align="justify">I faced many challenges throughout the coding phase of the project. I was unable to understand codes and unsure of why things were not going right. For a start, I was using “delay” function and “for” loop function to get the servo spinning properly. However, this became a problem when I had to introduce an emergency stop switch. As the delay function in Arduino essentially stops the program from running, my emergency stop will also be either delayed or not registered which poses as a huge problem. After consultation with Dennis, I was advised to not use “for” loop to move the servo so that the emergency stop can be registered during the movement of the servos. </p>
<p align="justify">Without knowing anything about Arduino boards, I had to go around asking what the pin does. For example, there are analog and digital pins that are essentially the same, but the main difference is the analog pin ability to read analog sensors. This was something that I did not know, and it slowed down my progress when programming. Furthermore, breadboards were commonly used in conjunction with Arduino boards. However, I was unsure of how to connect the wires and components such that it was linked resulting in time spent researching and watching videos that explained the connection behind breadboards. For example, we had to run test every time there was a change in the codes that affected the motors. However, we were unsure if it was the code or the connection between the Arduino board and component was wrong. Another example would be the push button. We did not know that there was a way connect it until Dennis instructed us to use a voltmeter to test and find the correct orientation. </p>
 

**Module:**

1.&nbsp;What have I learnt from the module

<p align="justify">Through this module, I learnt about the history of computers and am better able to understand the applications of computational is in our everyday lives. From this module, it is interesting to see how things that were taught in lectures were evident in our everyday lives. For example, the concept of procedural rhetoric. Most of times, we often just play games for the sake of entertainment. But through the lecture on Video Games, I learnt that a game can stimulate and change the way we think. For example, the game pong that we made during tutorial. To win, we must try and hit the ball along the edges of our racket to increase the speed of the ball and make it seem unpredictable for the computer to follow. This information is neither given nor told to the player, but it is conveyed via the gameplay. This made me realise that information can be transmitted through games and it is a viable option to use when it comes to educating young kids.</p>
<p align="justify">Another takeaway from this module would be the ability to code and understand codes better. At the start of the module, we were tasked to edit a game and include 2 different inputs such as touch, mouse, keyboard, voice and camera. Initially, it was tough as I had no background in computing and it was one of the first few tasks. However, Dennis was very patient and able to teach me how each individual function work and what it does. Also, the website’s ability to inform me of any error allowed me to slowly experiment and learn from my mistakes and understand the functions better. Eventually, I was able to edit the game by removing the voice input and inserting 2 different input namely keyboard and mouse input. Fast forward to the end of the semester, I was in charge of the coding portion of the project and had more opportunities to learn from my mistakes. </p>

2.&nbsp;What did I wish I could have added into my project to enhance its capabilities?

<p align="justify">The concept of “Written Rhetoric” would be one addition that could possibly enhance the capability. Having a screen that direct the drivers and also inform the drivers which process (eg. Washing or Scrubbing) of the car wash they are in. It can also display areas of the car being cleaned to give the drivers a sense of assurance that their car is being washed properly.
Another additional concept would be Virtual Reality. By entering the washing bay, cars can be seen as entering a virtual realm that helps to wash cars. This would act as an experience and entertainment for the drivers while they are waiting for their cars to be washed. </p>

3.&nbsp;Application as an Engineer

<p align="justify">From this module, it is evident that computational can applied in many fields including Engineering. For instance, the use of Augmented Reality (Feature Tracking) and Virtual Reality can be used to help engineers display finished products to their customers. Another technology would be digital fabrication which is already in place. Engineers are now using 3D printers and CNC mills to fabricate and print prototypes. </p>


### Jonathan Mohan (A0168550B)


**Project:**


1.&nbsp;Project Overview

<p align="justify">Our project idea started off in during the tutorial session about Physical Computing in week 7. During that tutorial class, we were introduced to the idea of Physical Computing and the idea explained through the video of the water droplets that were moved in various directions, under the user’s control. We decided to use “water” as our element using bits. As my partner was a driver and experienced the long waiting time during his car wash, we thought of having an Autonomous Car Washing System to replace the current system, saving precious time in the process. We wanted to create a simulation of how it might work in real life, using Arduino as the main source for this project. Our system works in a way that it would full autonomous process namely, detecting the arrival of a car, guiding the driver into the washing bay before going through a timed set of automatic procedures that will run based on our coding to ensure that it undergoes washing, soaping, scrubbing and a final rinse process. </p>

<p align="justify">We used Arduino as the basis of the project, with input sensors such as Proximity Sensor, Push buttons. The output sensors range from LED lights and servo motors. </p>

<p align="justify">The main objective of the project was to reduce manpower and labour cost, while at the same time seek to improve the washing efficiency during peak periods with the advancement of technology available in the market currently. Through this project we wanted to explore the boundaries of what we can really achieve without prior knowledge of coding and constructions of systems, while at the same time apply knowledge taught from this module. </p>

2.&nbsp;How does our project connect to ideas you have learned in this module?

<p align="justify">Personally, I feel that the most obvious connection would have to be the conversion from Bits to Atoms. The proximity sensor will send out a pulse and based on what it has received, it will be able to gauge the distance between the car and the washing bay. This result would help to trigger the rest of the proceeding car washing operations. It builts on to the application of Physical Computing in week 7 where the lectures and tutorials talked and show about how it is an interactive physical system using software and hardware that has the ability to sense and response to the analog world. </p>
<p align="justify">Furthermore, our project also touches on that aspect using Arduino. Arduino is a popular open source physical computing method consisting of a microcontroller board, sensors and a language which is used for the board’s programming. </p>
<p align="justify">Another element that was covered in the lectures was Visual Rhetoric. In our project, we applied that using different colours of the LED which were implemented to direct drivers in and out of the washing bay by informing them of the current occupancy. </p>

3.&nbsp;Analyze the affordances of digital media it uses

<p align="justify">After learning about the Janet Murray’s affordances in class, I would be analyzing the affordances of our own system in the project, namely Participatory, Spatial, Encyclopedic and Procedural. As our system is mainly a mock up prototype of the potential product, some affordances such as Encyclopedic and Spatial cannot be fully maximized. </p>

Participatory: LOW (Does not require much participating from the users as the program functions based on the proximity sensor distance reading, the only required input is the emergency stop and start button which would be activated by the staff) 
Spatial: MEDIUM (Takes in data from the proximity sensor based on the pulse sent out)
Encyclopedic: LOW (interaction through the code)
Procedural: HIGH (must follow a set of rules that is predetermined by our coding, or else the car washing operation would not be able to function efficiently)

4.&nbsp;How does it make use of the new abilities of computers?

How do you make use of computers (abilities) to make process fully automatic? 

5.&nbsp;How does it build off other projects you have seen?

<p align="justify">I did not have much prior knowledge of this system, and just wanted to find ways that my partner and I could improve existing systems to make it more efficient and user friendly also. Currently most car wash systems in the market are semi-autonomous, and through this project, we wanted to tap on the idea of making this car washing system a fully automatic procedure, improving its efficiency and reducing the manpower at the same time. </p> 

6.&nbsp;Challenges I faced throughout the project

<p align="justify">Prior to the start of this project, I did not have prior exposure to coding, with my only experience being taught C+ programming back in the Polytechnic. Hence it was difficult to work with my partner to brainstorm on ways to write the code in an efficient and precise manner. We spilt the project into 2 portions, namely the documentation + construction and the programming. My partner, Brandon took the programming portion and I helped him to research on the types of code required for our various sensors, such as servo motors and proximity sensors. Personally, I had difficulties with some of the hardware connections, eg: connecting the servo motor and proximity sensor wrongly and had to watch YouTube tutorials to get the wirings correct. Another example was the pushbutton. We had much difficulties in getting it to work, even though we read through various online forum posts and changed our programs. Dennis was the one that taught us the different between the ends of each Pushbutton “leg” and how we could use a voltmeter to test for the proper orientation. It was only through his guidance that we were able to understand the concept behind the pushbutton orientation and apply it properly in the project.</p>

<p align="justify">For the project documentation, I had to use GitHub to upload all information regarding our project. This was a challenge to me as I have been so used to working on documentation offline, and GitHub required some sort of coding to ensure the text appears in the way it should be. It took me a while to get the hang of the coding there as I had no prior experience to using mark-up language.  Furthermore, I had to research on how I could add pictures and videos using this coding language. This was a good challenge to me and I feel that with the knowledge I have learnt using GitHub, I could potentially further explore how I can use this as a platform for other documentations for the future. </p>

<p align="justify">Overall this project challenged me to step out of my comfort zone and explore new areas of computing and coding which I did not thought I would have learnt as an engineer. It also showed me the importance of teamwork, being on the same page as my teammate to ensure that our project was executed well before the project dateline. </p>

7.&nbsp;What further improvements could be made to my project to enhance it’s capabilities?

<p align="justify">If given a longer duration to execute the project, I would have preferred using CAD software such as Creo or AutoCAD to physically design the car washing bay, using the school’s 3D printer to fabricate the model instead of constructing it using Lego.  This would help to tie in with what I learnt in the Digital Fabrication lecture and at the same time give me a chance to learn more about the fabrication processes behind 3D Printing. </p>

<p align="justify">Furthermore, instead of simulating the washing procedure using the servo motors, there is further room to explore how I could implement the use of motion control to allow the motor to “interact” with the car and it’s surroundings better. This would be something that will make our system stand out, while at the same time test my coding and fabrication abilities. </p>
 

**Module:**

1.&nbsp;What have I learnt from the module and felt challenging?

<p align="justify">I came into this module with not much expectations, as I did not have much prior knowledge and experience with Computer Literacy. Personally, I did not even understand what it meant and thought this module would be a good opportunity to learn more about computers and digital media.  Though that was true partially, I found myself exploring more into the various aspects of technologies that make up computational media and enjoying myself in the process. After this module, I find myself being more inquisitive about the systems that are in place in our daily life and have a better appreciation for how computation enhances key features of modern living. As an individual who has a robotics background and an avid photographer, I found topics such as Intellectual property, social media, digital fabrication very applicable to my life. Both the technical and practical aspects of this module allowed me to think of new ways to expand and develop of the ideas currently on the market.</p>

<p align="justify">The peer presentations / tutorials sessions also allowed me to learn new topics and skills in the classroom. I personally enjoyed the photoshop tutorial done in one of my tutorial class when I learnt how to further manipulate images using photoshop. Furthermore, challenges such as “creating” a computer game from scratch was also a good way for me to step out of my comfort zone and practically test my understanding of the applications of coding. Personally, I found topics such as Physical computing which included Tangible User Interface (TUI) and Graphical User Interface (GUI) particularly challenging. I could not really grasp the idea of both interfaces and found it hard to apply it to my daily life and project in general. </p>

2.&nbsp;Module Application as an Engineer

<p align="justify">As an engineering student, there is a vast majority of content in this module that I find applicable to my studies. The advancement technology coupled with Augmented Reality and Virtual Reality allows future engineers like myself an opportunity to make our 3D models come to life without having to fabricate an actual prototype. This would allow more efficient workflow and increase productivity for future design jobs. </p>

<p align="justify">Another important aspect of engineering work is programming / coding. This module has really given me the opportunity to learn new forms of coding which would be very useful in my future profession. With so many applications and appliances linked to technology and computer these days, this module provided me with a better understand of possible ways that I can interact with them, maximising the products full potential.</p>


