# Garbage-Monitoring-System

#### Project works on real-time database which uses real-time processing to monitor whether the system is full or not. 😀
#### It is connected with both App and Website. They both tell the user about the percentage of space that has been used and notifies the user when its time to clean the dustbin by sending a message, e-mail and  notification on phone. 📱👩‍💻
#### System must be connected to Wifi for data processing. All the previous data is saved on the cloud server so that the user can monitor the behaviour of the system (chart graphs are available with different time variations).
#### Materials Required :- NodeMCU, HC-SR04, Servo Motor, IR Sensor, Arduino UNO, Jumper Wires, Bread Board, USB Cable, USB cable type A/B
#### Software Required :- Arduino IDE
#### Working:-
###### An ultrasonic sensor will be placed on the interior side of the lid, the one facing the solid waste. As trash increases, the distance between the ultrasonic and the trash decreases. This live data will be sent to our app and website.
###### IR-Sensor detects if anyone's standing in front of the system or not. It sends the information to servo and servo opens up the lid.
