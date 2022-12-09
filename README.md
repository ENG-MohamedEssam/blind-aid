# blind-aid

## Abstract 

#### This project was mainly split into two parts, the first one is using machine learning to identify 80 different objects and the code was working properly on the laptop and for future intentions i was going to move it to work on raspberry pi.
#### The second part was using small microcontroller to make the device cheaper and easy to aquire by many people, this part was meant to replace the stick that the blind would use by a small ring to wear in your hand.

## What are the components of the ring ?
#### mainly it has it's controller which is Atmega328p, A small potentiometer, a dip switch, a vibration motor like the ones in the mobile phones, and a laser sensor (VL53L0X Time of Flight Sensor) which has up to 2m percison distance

## How does the ring work?

#### The ring turns on/off using a switch when you point it to a rigid object it gives a sense of vibration to your hand and when you get closer to the object the ring vibrates even more and that gives you the sense of how close the object is to your hand.
### Note that  #### You can adjust the sensetivity of the device using the small potentiometer that's on the ring

#### I designed the ring on SolidWorks as you can see below
![img](https://github.com/ENG-MohamedEssam/blind-aid/blob/main/images/solid1.jpeg)
![img](https://github.com/ENG-MohamedEssam/blind-aid/blob/main/images/solid3.jpeg)
#### The board should take the top of the ring as it's housing and the bottom of the ring is meant for the laser sensor
#### I 3D-printed the ring as you can see below
![img1](https://github.com/ENG-MohamedEssam/blind-aid/blob/main/images/3dpart1.jpeg)
![img2](https://github.com/ENG-MohamedEssam/blind-aid/blob/main/images/3dpart3.jpeg)
#### And the follwing is the design of the board
![top](https://github.com/ENG-MohamedEssam/blind-aid/blob/main/images/brdtop.jpeg)
![bottom](https://github.com/ENG-MohamedEssam/blind-aid/blob/main/images/brdbtm.jpeg)
![pcb1](https://github.com/ENG-MohamedEssam/blind-aid/blob/main/images/brddesign1.jpeg)
![pcb2](https://github.com/ENG-MohamedEssam/blind-aid/blob/main/images/brddesign2.jpeg)
#### The ring worked perfectly on a breadboard and for future intentions the board will be made and the product will be finished soon.
