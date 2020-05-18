# Project 2 : Building a Weather station 
### Problem Statement:
To build a Weather Station that displays weather information and predicts forthcoming weather situations.     
### Ideation:
In the actual project, a Raspberry Pi is used to collect information from the Web and to drive a display for displaying the weather information. We can also upload the data to a third-party open IoT platform and access it. Here we are using the ability of network connectivity of Raspberry Pi and IoT. We can additionally use sensors to detect Temperature, Humidity (DHT11) and Pressure (BMP180). This data can be read by the Raspberry Pi and processed, in addition to the data gathered from the Web. This data can be made available to the user through an third-party open source IoT platform (like ThingSpeak). Locally the data can be displayed on an LCD driven by the Raspberry Pi.
###### An alternative approach: 
We can use a low-cost, open source IoT module like NodeMCU to collect data from the Web and uploading it to an open, online IoT platform. In addition, we can also connect sensors to detect Temperature,Humidity (DHT11) and Pressure (BMP180) to the NodeMCU to monitor local data and it can be uploaded to the online IoT platform as well.      
We can use a Bolt IoT module which can gather this data from the online platform to it's cloud and process it to display the weather information that has been gathered locally through sensors and through the Web and the user can access it from anywhere.    
We can also serially add a microcontroller to the Bolt IoT module to drive a display locally, displaying the weather information.    

The Bolt IoT module and NodeMCU together cost less than Raspeberry Pi and hence can be considered as a cost-effective alternative.   
Note : The Bolt IoT module has it's own cloud platform for data usage and storage while Raspberry Pi depends on a third-party IoT platform.
These modules are also smaller in size compared to Raspberry Pi. Power comsumption is also reduced by using NodeMCU and it allows high speed interfacing of sensors too.   
##### Personal Notes:
Since this project doesn't involve any heavy processing of data, using NodeMCU instead of Raspberry Pi reduces the cost significantly. So, NodeMCU can be extensively used for this project instead of Raspberry Pi.  



                              
