# Introduction 

Even though there are  precautions are taken during Fire accidents,  natural/man-made disasters do occur now and then. In the event of a fire breakout, to rescue people and to put out the fire, we are forced to use human resources which are not safe. With the advancement of technology especially in robotics it is very much possible to replace humans with robots for fighting the fire. This would improve the efficiency of firefighters and would also prevent them from risking human lives we are going to build a Fire Extinguishing Robot using Arduino, which will automatically detect fire with the help of infrared sensors and start the water pump to extinguishing the fire.

# Hardware Requirements 
- Arduino UNO
+ IR Fire sensor 
* Servo Motor
- L293D motor Driver module
+ Mini DC Submersible Pump
* Robot chassis with motors 

# Software Requirement
+ Arduino IDE


# Block Diagram

![image](https://user-images.githubusercontent.com/77841585/210152855-2b012caa-cd65-40ae-b039-84ff605a571d.png)

# Working

- Initially, the IR sensors detect the presence of fire and provide input to the Arduino Uno.
- Arduino acts as a central command and based on the input and the algorithm uploaded to the Arduino, it will accordingly power the motors of the robot (to move) and the water pump (to pump the water). 
- A servo provides a 180 sweep directing the water tube, thereby extinguishing the fire.

# Result

![12](https://user-images.githubusercontent.com/77841585/210153211-232a9d63-e31a-4191-b37b-8539cd38e67d.jpg)
