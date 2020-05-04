# Project 2 : Building a Weather station 
### Problem Statement:
To build a Weather Station that displays weather information and predicts forthcoming weather situations.     
### Ideation:
This problem can be solved in the following ways:
1) A rather trivial way of using sensors to detect factors like temperature, pressure and humidity; collecting this data and then suitably processing it to get the weather details.
2) Fetching the data from the internet and displaying it 
3) An elaborate way - An IoT based solution to monitor data from the sensors as well as predicted weather forecasts. 
##### Pipeline: 
Data Acquisition (from sensors) --> Microcontroller (Receiver end - to periodically read the data)       
                                --> Transmitting IoT Module <-- Data Acquisition (from the Web)      
                                --> Microcontroller (To gather information and drive the display) --> Display (User Interface)
                                
                              
