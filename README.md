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

![](Raspberry_pi3.jpg "Raspberry pi 3")
<center>Image source: [@00000004]</center>

![](Arduino_mega2560.jpg "Arduino mega2560")
<center>Image source: [@00000005]</center>

![](steppermotor.jpg "Bi-polar Stepper motor")
<center>Image source: [@00000006]</center>


FarmBot will be able to perform the following task:



-   Monitor the temperature around the plant,

-   Provide light to the plant.

The hardware component for FarmBot that We have are:

-   Raspberry pi 3 – It is used to receive data from FarmBot and send it to the
    Arduino


	
-   Arduino mega 2560 – It is used to control the bi-polar stepper motor




-   Sensor Hat (light and temperature) – It is used to receive data about light
    and temperature from surrounding.

-   Bi-polar Stepper motor – It controls the movement of the FarmBot



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

We plan on first tightening a pulley to my bi-polar, then create a pulley system
with the motor and a case.

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

**Methodology**

This proposal is assigned in the first week of class and is due at the beginning
of class in the second week of the fall semester. My coursework will focus on
the first two of the 3 phases of this project:  
Phase 1 Hardware build.  
Phase 2 System integration.  
Phase 3 Demonstration to future employers.

*Phase 1 Hardware build*

The hardware build will be completed in the fall term. It will fit within the
CENG Project maximum dimensions of 12 13/16" x 6" x 2 7/8" (32.5cm x 15.25cm x
7.25cm) which represents the space below the tray in the parts kit. The highest
AC voltage that will be used is 16Vrms from a wall adaptor from which +/- 15V or
as high as 45 VDC can be obtained. Maximum power consumption will be 20 Watts.

*Phase 2 System integration*

The system integration will be completed in the fall term.

*Phase 3 Demonstration to future employers*

This project will showcase the knowledge and skills that we have learned to
potential employers.

The tables below provide rough effort and non-labour estimates respectively for
each phase. A Gantt chart will be added by week 3 to provide more project
schedule details and a more complete budget will be added by week 4. It is
important to start tasks as soon as possible to be able to meet deadlines.

| **Labour Estimates**                                                                                                                                                                                                                                                                                                                  | **Hrs**        | **Notes**                                                                                                                      |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|--------------------------------------------------------------------------------------------------------------------------------|
| **Phase 1**                                                                                                                                                                                                                                                                                                                           |                |                                                                                                                                |
| Writing proposal.                                                                                                                                                                                                                                                                                                                     | 9              | Tech identification quiz.                                                                                                      |
| Creating project schedule. Initial project team meeting.                                                                                                                                                                                                                                                                              | 9              | Proposal due.                                                                                                                  |
| Creating budget. Status Meeting.                                                                                                                                                                                                                                                                                                      | 9              | Project Schedule due.                                                                                                          |
| Acquiring components and writing progress report.                                                                                                                                                                                                                                                                                     | 9              | Budget due.                                                                                                                    |
| Mechanical assembly and writing progress report. Status Meeting.                                                                                                                                                                                                                                                                      | 9              | Progress Report due (components acquired milestone).                                                                           |
| PCB fabrication.                                                                                                                                                                                                                                                                                                                      | 9              | Progress Report due (Mechanical Assembly milestone).                                                                           |
| Interface wiring, Placard design, Status Meeting.                                                                                                                                                                                                                                                                                     | 9              | PCB Due (power up milestone).                                                                                                  |
| Preparing for demonstration.                                                                                                                                                                                                                                                                                                          | 9              | Placard due.                                                                                                                   |
| Writing progress report and demonstrating project.                                                                                                                                                                                                                                                                                    | 9              | Progress Report due (Demonstrations at Open House Saturday, November 7, 2015 from 10 a.m. - 2 p.m.).                           |
| Editing build video.                                                                                                                                                                                                                                                                                                                  | 9              | Peer grading of demonstrations due.                                                                                            |
| Incorporation of feedback from demonstration and writing progress report. Status Meeting.                                                                                                                                                                                                                                             | 9              | 30 second build video due.                                                                                                     |
| Practice presentations                                                                                                                                                                                                                                                                                                                | 9              | Progress Report due.                                                                                                           |
| 1st round of Presentations, Collaborators present.                                                                                                                                                                                                                                                                                    | 9              | Presentation PowerPoint file due.                                                                                              |
| 2nd round of Presentations                                                                                                                                                                                                                                                                                                            | 9              | Build instructions up due.                                                                                                     |
| Project videos, Status Meeting.                                                                                                                                                                                                                                                                                                       | 9              | 30 second script due.                                                                                                          |
| **Phase 1 Total**                                                                                                                                                                                                                                                                                                                     | **135**        |                                                                                                                                |
| **Phase 2**                                                                                                                                                                                                                                                                                                                           |                |                                                                                                                                |
| Meet with collaborators                                                                                                                                                                                                                                                                                                               | 9              | Status Meeting                                                                                                                 |
| Initial integration.                                                                                                                                                                                                                                                                                                                  | 9              | Progress Report                                                                                                                |
| Meet with collaborators                                                                                                                                                                                                                                                                                                               | 9              | Status Meeting                                                                                                                 |
| Testing.                                                                                                                                                                                                                                                                                                                              | 9              | Progress Report                                                                                                                |
| Meet with collaborators                                                                                                                                                                                                                                                                                                               | 9              | Status Meeting                                                                                                                 |
| Meet with collaborators                                                                                                                                                                                                                                                                                                               | 9              | Status Meeting                                                                                                                 |
| Incorporation of feedback.                                                                                                                                                                                                                                                                                                            | 9              | Progress Report                                                                                                                |
| Meet with collaborators                                                                                                                                                                                                                                                                                                               | 9              | Status Meeting                                                                                                                 |
| Testing.                                                                                                                                                                                                                                                                                                                              | 9              | Progress Report                                                                                                                |
| Meet with collaborators                                                                                                                                                                                                                                                                                                               | 9              | Status Meeting                                                                                                                 |
| Prepare for demonstration.                                                                                                                                                                                                                                                                                                            | 9              | Progress Report                                                                                                                |
| Complete presentation.                                                                                                                                                                                                                                                                                                                | 9              | Demonstration at Open House Saturday, April 9, 2016 10 a.m. to 2 p.m.                                                          |
| Complete final report. 1st round of Presentations.                                                                                                                                                                                                                                                                                    | 9              | Presentation PowerPoint file due.                                                                                              |
| Write video script. 2nd round of Presentations, delivery of project.                                                                                                                                                                                                                                                                  | 9              | Final written report including final budget and record of expenditures, covering both this semester and the previous semester. |
| Project videos.                                                                                                                                                                                                                                                                                                                       | 9              | Video script due                                                                                                               |
| **Phase 2 Total**                                                                                                                                                                                                                                                                                                                     | **135**        |                                                                                                                                |
| **Phase 3**                                                                                                                                                                                                                                                                                                                           |                |                                                                                                                                |
| Interviews                                                                                                                                                                                                                                                                                                                            | TBD            |                                                                                                                                |
| **Phase 3 Total**                                                                                                                                                                                                                                                                                                                     | **TBD**        |                                                                                                                                |
| **Material Estimates**                                                                                                                                                                                                                                                                                                                | **Cost**       | **Notes**                                                                                                                      |
| **Phase 1**                                                                                                                                                                                                                                                                                                                           |                |                                                                                                                                |
| A microcomputer composed of a quad-core Windows 10 IoT core compatible Broadcom BCM2836 SoC with a 900MHz Application ARM Cortex-A7 32 bit RISC v7-A processor core stacked under 1GB of 450MHz SDRAM, 10/100 Mbit/s Ethernet, GPIO, UART, I²C bus, SPI bus, 8 GB of Secure Digital storage, a power supply, and a USB Wi-Fi adaptor. | \>\$80.00      | An example of a retailer: [3].                                                                                                 |
| Peripherals with cables                                                                                                                                                                                                                                                                                                               |                |                                                                                                                                |
| Sensors                                                                                                                                                                                                                                                                                                                               |                |                                                                                                                                |
| Actuators                                                                                                                                                                                                                                                                                                                             |                |                                                                                                                                |
| Hardware, etc.                                                                                                                                                                                                                                                                                                                        |                |                                                                                                                                |
| **Phase 1 Total**                                                                                                                                                                                                                                                                                                                     | **\>\$200.00** |                                                                                                                                |
| **Phase 2**                                                                                                                                                                                                                                                                                                                           |                |                                                                                                                                |
| Materials to improve functionality, fit, and finish of project.                                                                                                                                                                                                                                                                       |                |                                                                                                                                |
| **Phase 2 Total**                                                                                                                                                                                                                                                                                                                     | **TBD**        |                                                                                                                                |
| **Phase 3**                                                                                                                                                                                                                                                                                                                           |                |                                                                                                                                |
| Off campus colocation                                                                                                                                                                                                                                                                                                                 | \<\$100.00     | An example: [4].                                                                                                               |
| *Shipping*                                                                                                                                                                                                                                                                                                                            | *TBD*          |                                                                                                                                |
| *Tax*                                                                                                                                                                                                                                                                                                                                 | *TBD*          |                                                                                                                                |
| *Duty*                                                                                                                                                                                                                                                                                                                                | *TBD*          |                                                                                                                                |
| **Phase 3 Total**                                                                                                                                                                                                                                                                                                                     | **TBD**        |                                                                                                                                |







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


