INSTALLATION:
GET THE HARDWARE SETUP COMPLETLY

Download Arduino IDE : https://www.arduino.cc/en/software
OPEN the _ino file.
Upload to ARDUINO


Arduino Gas and Temperature Decdector


Project Title: Android based Industrial fault monitoring system

Abstract:
Now a day, automation is a major element in the industry. Human efforts are reduced with the contraption of  automation machine which monitors and detects any faults in the system. Here we procreate a similar automation machine for use in industries for monitoring numerous parameters which includes temperature, humidity and lpg gas leak.
 First sensor is LPG Gas sensor and second sensor is Temperature sensor.  If any one of these sensors has crossed threshold level then a buzzer is turned on and at the same time a warning intimation is sent to a android mobile. We use a Bluetooth module to communicate with android app. We provide a actual time non-forestall tracking of the parameters on the android show. 
KEYWORDS: Microcontroller, Sensors, Android Operating System, Bluetooth device, Controlling Device.
 
Introduction: 
 The main objective of the industry automation project using embedded system that uses Microcontroller which provides intelligent fault monitoring system, “IOT based monitoring system for industry automation” which is capable of controlling and automating most of the industry appliances through an easy manageable smart phone based android interface. The proposed system has a great flexibility which uses bluetooth technology to interconnect its distributed sensors to industry automation server. This will reduce the deployment cost and will increase the ability of upgrading, and system reconfiguration. Our proposed IOT based automation system not only reduces overall cost because of Controller which when used in distributed environment drastically reduces project cost because of cheaper components used, also it upgrades and does auto-system reconfiguration. The use of embedded system using Microcontroller reduces project cost because it is cheaper in cost compared to other embedded systems controlling IOT. Already developed IOT based projects systems, faces four main challenges; these are high cost of ownership, inflexibility, poor manageability, and difficulty in achieving authorization security. This proposed system presents a low cost and flexible automation machine using an embedded microcontroller web server, with bluetooth connectivity for accessing and controlling devices and appliances remotely using Android based Smart phone application. This proposed and implemented system require a dedicated server PC and offers a novel communication protocol to monitor and control the industry environment with more than just the switching functionality. To demonstrate the feasibility and effectiveness of this system, devices such temperature sensor and gas sensors have been integrated with the proposed automation system.


Literature Review: 
The systems objectives outlined during the feasibility study serve as the basic from which the work of system design is initiated. Much of the activities involved at this stage is of technical nature requiring a certain degree of experience in designing systems, sound knowledge of computer related technology and through understanding of computers available in the market and the various facilities provided by the vendors. Nevertheless, a system cannot be designed in isolation without the active involvement of the user. The user has a vital role to play at this stage too. As we know that data collected during feasibility study wills we utilized systematically during the system design. It should, however be kept in mind that detailed study of the existing system is not necessarily over with the completion of the feasibility study. Depending on the plan of feasibility study, the level of detailed study will vary and the system design stage will also vary in the amount of investigation that still needs to be done. This investigation is generally an urgent activity during the system. Sometimes, but rarely, this investigation may form a separate stage between feasibility study and computer system design. Designing a new system is a creative process, which calls for logical as well as lateral thinking. The logical approach involves systematic moves towards the end product keeping in mind the capabilities of the personnel and the equipment at each decision making step. Lateral thought implies encompassing of ideas beyond the usual functions and equipment. This is to ensure that no efforts are being made to fit previous solutions into new situations. 
Problem Statement:


Objective:
To design a IOT based monitoring system for industry automation.

Methodology:
This project is a combination of hardware system and android application. Hardware and android communicate using Bluetooth module. At hardware aspect we use Bluetooth module and the in-construct Bluetooth of Android cellular is used. In this to construct the android app we use Android Studio software program. Android app GUI indicates the values of parameters. It will have a start and stop buttons to turn on and turn off the basic devices. When we press the start button on the GUI internal timer starts and the android app connects with the hardware Bluetooth and sends command to the read each all sensor. Two sensors provide analog values which are tempeture and gas. The digital value gives gas and temperature. If all the sensor exceed there range then automatically value displayed on android application this application can be turned on basic device.

	                             


	Phase name				Time duration
1.Feasibility study					1 week
2.System requirement and analysis	               1 week
3.Design
       Module 1: Communication interface
       Module 2: Bluetooth device set up
       Module 3: Working with Android Studio. 	               
           					   3 weeks
4.Coding and unit testing	         	     4 weeks
5.Integration and system testing	             2 weeks
6.Maintenance	        			    3 weeks


System Requirements: (Hardware)
1) Microcontroller
2) Android mobile with application installed.
3) Bluetooth Receiver and decoder for Wireless communication
4) LCD Display
5) LPG gas sensor
6) Temperature sensor
7) Buzzer
