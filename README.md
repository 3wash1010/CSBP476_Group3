Spring 2025 – CSBP476 Final Project – Robotics Competition Phase II

Team Members
•	Amal – GitHub: @lamanami
•	Ayesha – GitHub: @3wash1010
•	Hibaq – GitHub: @HibaqY
•	Rawdha – GitHub: @Rawdha-ai

Project Summary
•	This project was developed as part of the CSBP476 'Robotics & Intelligent Systems' course. Our robot uses sensors and preprogrammed logic to autonomously navigate a line-following arena, detect obstacles, and adjust behavior based on detected paths and competition rules.

Robot Features
•	Autonomous line following using infrared sensors
•	Obstacle detection using an ultrasonic sensor
•	Mode selection based on analog input
•	LED and buzzer feedback
•	Two motor differential drive

Flowchart 
• The flowchart illustrates our robot's decision-making logic for line tracking and obstacle detection.

Video Demo 
• The video contains the full demo of our robot performing in the competition arena. The last few seconds of the video include the 'Obstacle detection and stop' task.
• The YouTube link is also provided in addition to the attached video -> https://youtube.com/shorts/2UI09Hn9rG4?feature=share

Code Overview
•	'Code' – Contains the complete logic for:
o	Initialization of sensors and motors
o	Mode selection
o	Continuous sensor reading and conditional motor control
o	Obstacle detection and reset behavior
•	The robot handles two modes (mode = 1 or mode = 2) and uses conditional logic to react accordingly.

Robotics project final.mblock
• This file contains the Block-Based code used on the mBot that can opened using the mBlock IDE

Hardware Used
•	mBot (MakeBlock)
•	Ultrasonic Sensor
•	Line Follower Sensor
•	RGB LED
•	Buzzer
•	Dual DC Motors
•	Arduino-compatible controller

Tasks Completed
•	Obstacle detection and stop
•	Resume after obstacle cleared
•	Line following with adjustments for deviation
•	Mode indication using LED and buzzer
