---
csl: apa.csl
bibliography: RPiCitations.bib
---


Projects website: http://StudentEng2016.github.io/

FarmBot
=======

![](farmbotv2.png "FarmBot")
<center>Image source: [@00000001]</center>

**From: Alisha Singh Chauhan, Adanegbe Amadasun**

**Discipline: Computer Engineering Technology**

**Date Submitted: March 03,2017**


Declaration of Joint Authorship 
===============================

We, Alisha Singh Chauhan and Adanegbe Amadasun students of Applied Technology department
hereby declare that the following technical report submitted for CENG 355 
Computer Systems Project is expressed in our own words.  
The work which has been used from various sources like: words, numerical data, figures, tables etc. 
has been either paraphrased or cited separately. The original sources of cited work may be located
using IEEE style in References page at the back.


Executive Summary
=================

As a student in the Computer Engineering Technology program, we will be
integrating the knowledge and skills we have learned from our program into this
Internet of Things themed capstone project. This proposal requests the approval
to build the hardware portion that will connect to a database as well as to a
mobile device application. The internet connected hardware will include a custom
PCB with sensors and actuators for an automated farming device. The mobile
device functionality will include will include photo sensors, temperature
sensors and moisture sensors which will be and will be further detailed in the
mobile application proposal. We will be collaborating with the following
company/department. In the winter semester I plan to form a group with the
Alisha Singh Chauhan who is also building similar hardware
this term and working on the mobile application with me. The hardware will be
completed in CENG 317 Hardware Production Techniques independently and the
application will be completed in CENG 319 Software Project. These will be
integrated in CENG 355 Computer Systems Project.


Table of Contents
=================

1.  [Introduction](#Introduction)
2.  [Body](#Body)

	2.1[Purpose](#Purpose)
	
	2.2[Hardware Specification](#Hardware Specification)
	
	2.3[Software  Specification](#Software  Specification)


List of Illustrations
=====================

-	Figure 1:  FarmBot
-	Figure 2:  Detailed Farmbot diagram
-	Figure 3:  Parts of a FarmBot
-	Figure 4:  Raspberry pi 3
-	Figure 5:  Arduino mega2560
-	Figure 6:  Bi-polar Stepper motor


1. Introduction
------------
An open source automated farming device which operates like a 3D printer. But
instead of extruding plastic, its tools are seed injectors, watering nozzles,
sensors etc.

FarmBot is going to address some the problems the agricultural industry faces
like lost of money, how ineffective some of their equipment are and how they
waste resources. FarmBot is going to be more economical and ecofriendly unlike
other agricultural equipment being used. It incorporates precision farming,
which happens to be a concept based on observing, measuring and responding to
inter and intra-field variability in crops. The device is going to be
constructed be the FarmBot company, it is going to be made of an Arduino Mega
2650, Raspberry Pi 3, disassembled hardware packages and other software sources.
The FarmBot Genesis runs on custom built tracks and other supporting
infrastructure which needs to be self assembled. The robot itself relies on a
GUI platform which users can access through the FarmBot’s web app. The physical
robotic system is set in alignment with the crops that are plotted out in the
virtual version on the web app. This is how FarmBot can be efficient and
reliably distribute water, fertilizer and other elements to keep the plants
healthy and striving without minimal wastage. The device is going to be cheaper
than convention tools and more efficient.




We have searched for prior art via Humber’s IEEE subscription selecting “My
Subscribed Content” [@5306920] and have found and read [@7059344] which provides
insight into similar efforts.

In the Computer Engineering Technology program, we have learned about the
following topics from the respective relevant courses:

-   Java Docs from CENG 212 Programming Techniques In Java,

-   Construction of circuits from CENG 215 Digital And Interfacing Systems,

-   Rapid application development and Gantt charts from CENG 216 Intro to
    Software Engineering,

-   Micro computing from CENG 252 Embedded Systems,

-   SQL from CENG 254 Database With Java,

-   Web access of databases from CENG 256 Internet Scripting; and,

-   Wireless protocols such as 802.11 from TECH152 Telecom Networks.

This knowledge and skill set will enable me to build the subsystems and
integrate them together as my capstone project.

2. Body
----

**2.1 Purpose**

FarmBot is going to address some the problems the agricultural industry faces
like lost of money, how ineffective some of their equipment are and how they
waste resources.


**2.2 Hardware Specification**

![](FarmBotSystem2.jpg "FarmBot Structure")
<center>Image source: [@00000003]</center>

![](FarmBotSystem3.jpg "Parts for FarmBot")
<center>Image source: [@00000002]</center>
(Describe farmbot parts)


FarmBot will be able to perform the following task:


-   Monitor the temperature around the plant,

-   Provide light to the plant.

The hardware component for FarmBot that We have are:

-   Raspberry pi 3 – It is used to receive data from FarmBot and send it to the
    Arduino
	
![](Raspberry_pi3.jpg "Raspberry pi 3")
<center>Image source: [@00000004]</center>

	
-   Arduino mega 2560 – It is used to control the bi-polar stepper motor

![](Arduino_mega2560.jpg "Arduino mega2560")
<center>Image source: [@00000005]</center>


-   Sensor Hat (light and temperature) – It is used to receive data about light
    and temperature from surrounding.

-   Bi-polar Stepper motor – It controls the movement of the FarmBot

![](steppermotor.jpg "Bi-polar Stepper motor")
<center>Image source: [@00000006]</center>

**2.3 Software  Specification**

**2.3.1 Database Work Breakdown**

Currently, We only have a local database for our FarmBot project. The database
stores the plant number, date, and name locally. Once the app is deleted the
users will lose access to all their data.

We plan on getting a server to so all users data can be stored in the cloud and
can be accessed by them at any time

**2.3.2 Application and work breakdown**

FarmBot is going to be more economical and ecofriendly unlike other agricultural
equipment being used. It incorporates precision farming, which happens to be a
concept based on observing, measuring and responding to inter and intra-field
variability in crops. The device is going to be constructed be the FarmBot
company, it is going to be made of an Arduino Mega 2650, Raspberry Pi 3, Sensor
hat (which can read temperature, light, and soil condition), and Bi-polar
stepper motor.

We plan on using the an arduino mege2560 to control the bi-polar stepper motor 
to make it move on its X-axis 

**2.3.3 Web and work breakdown**

An app was created to use for the FarmBot, this app would be used to control the
FarmBot to plant seed at desire position in the bed. Also, the user can choose
the option of giving the FarmBot light for a duration of time, watering the
plant etc.

After installing the app on your mobile phone, users will be prompt to create an
account by choosing user name and password. This will then give them access to
their FarmBot and its data stored in the cloud.

The user can then pick the seed of the crop they want to plant, and the care
option they want to apply to the seed (i.e. The light duration, or how
frequently they want to water the plant) and submit the options they picked

The user would be given the access to control the FarmBot and apply the option
picked from the previous screen.

We plan on connecting FarmBot’s app with raspberry pi, so that users can be able
to send data to it.


**Concluding remarks**

This proposal presents a plan for providing an IoT solution for FarmBot This is
an opportunity to integrate the knowledge and skills developed in our program to
create a collaborative IoT capstone project demonstrating my ability to learn
how to support projects. We request the approval of this project.

**References**

These are the references We am going to use for the duration of this project,
though if we come across other references we will add them.

[@5306920]

[@7059344]

[@12345678]

[@00000002]

[@00000001]

[@00000003]


