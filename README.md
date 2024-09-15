# SmartDoorLockSystem
A FingerPrint and Facial Door Lock System Using Raspberry Pi

Our project deals with the design and implementation of a two-level secure locking system using Raspberry Pi. The module contains a secured face recognizer and authenticate finger print system for automatic door unlocking. Only when both fingerprint and face recognition inputs match with an authorised user, the door lock gets unlocked. This provides essential security to our homes, workplaces, bank lockers etc and sends alert through the LED module. 

# HARDWARE COMPONENTS REQUIRED:
1.	Raspberry Pi
2.	Fingerprint Scanner with board
3.	Relay Module
4.	Green and Red LED 
5.	Jumper wires
6.	Pi Camera
7.	Motor
# SOFTWARE REQUIRED:
1.	Open CV
2.	Python IDE
3.	
# FACE RECOGNITION SYSTEM DESCRIPTION:
There are few objectives to design the face detection system. The objectives are:
1. To design real time face detection system. 
2. To utilize the face detection system based on Haar classifier. 
3. To develop face detection system using open CV. 

# Cases handled

Case 1: When an unauthorized fingerprint is given as input, “Unauthorized” is printed in the command line and the door remains locked. Red LED lights up. This case is demonstrated in the video named “unauthorized fingerprint_demo” and “unauthorized fingerprint_demo2”.
Case 2: When an authorised fingerprint and an unauthorized face recognition are given as inputs, “Unauthorized” is printed in the command line and the door remains locked. Red LED lights up. This case is demonstrated in the video named “authorized fingerprint_unauth face_demo.”
Case 3: When both the fingerprint and face recognition inputs are matched, then the user is an authorized person and the door lock unlocks. The command line prints the name of the user, say user-1 or user-2. Green LED lights up. This case is demonstrated in the video named “demo_embedded”.


