# fpbbot1
Code and description of making a FPV bot powered by Arduino Nano 

 The code controls a bot with two 1000 rpm Dc brushed geared motor 
 * Arduino Nano is connected to a L298 motor driver via ports 5,6,7,8,9,10 (9,10 are Enable pins)
 * 2.4 Ghz Rc Receiver is connected to port 3,4 with ch2 controlling the forward movement of the bot and is connected to elevator channel
 * ch3 controls the turn and is connected to yaw channel of the transnitter.
 * A FPV system(5.8gHZ analog system) has been connected to the bot which sends live camera feed to the video goggles
 * Power by a 3 cell(11.1 volt) Li-Ion battery 
