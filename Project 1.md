# Gesture Controlled Wheelchair:
### Problem Statement: 
To develop a prototype for a robotic wheelchair that can be controlled using simple hand gestures. Each hand gesture is used for a specific movement of the wheelchair.
### Ideation:
Hand Movement/Gesture detection --> Microcontroller (Transmitting End-Hand module) --> Wireless Communication Module --> Microcontroller (Receiving End-Wheelchair module) --> Motor driver --> Motors (Wheelchair movements)
  
  |    Part of Pipeline        |      Feasibility             |      Advantages               |     Disadvantages                     |
  |----------------------------|------------------------------|-------------------------------|---------------------------------------|
  |  Gesture Detection: Accelerometer + Gyroscope | Excellent tool for measuring the orientation of an object in 3D space| Access to accurate orientation information for translating real-world movements into the virtual world. Small,light and fast in operation| Relatively expensive. MEMS versions are cheaper but are less stable over temperature and stress|
  |Microcontroller | Quite easy to handle | Relatively Cheap and easily programmable for specific uses  | A bit difficult for beginners to understand and code|
  |Wireless Communication | Various methods and required modules are easily available | RF modules are small, have wide operating voltagte range and consume less power. Bluetooth modules can also be used. They have quick connectivity, good operating range and are relatively cheap| RF modules operate over less distance. The modules have to be duly interfaced for data transfer. Bluetooth modules involve security issues since anyone can connect to it|
  
  The project solution is fairly good to implement. An Arduino Nano is used in the Hand module along with a MPU6050 Accelerometer+Gyroscope. An Arduino Uno at the receiving end is used to send the instructions to the motor drivers. The communication between the Nano and Uno could be set up in two ways:
  1) Using an RF Module : These modules are relatively cheap and work well over a short range of distance. Since we'll be operating over a short range, this is not a problem. The transmitter and receiver have tobe aligned for data transfer. The construction has to be done in such a way that the modules are duly interfaced. They also consume low power as they only function during the data transfer.
  2) Via Bluetooth : This doesn't involve any construction constraints and also doesn't consume much power. But it involves security issues as anyone can connect to the module.    
    
So, I would choose RF Communication since distance is not much of an issue here. Also, simple arrangements in construction can be done to avoid environmental interferences with the data transfer. 
