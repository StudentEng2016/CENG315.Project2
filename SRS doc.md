**Student Name: Adanegbe Amadasun**


**SRS Document**

**Purpose**

FarmBot is going to address some the problems the agricultural industry faces
like lost of money, how ineffective some of their equipment are and how they
waste resources.

**Definitions**

An open source automated farming device which operates like a 3D printer. But
instead of extruding plastic, its tools are seed injectors, watering nozzles,
sensors etc.

**System Specification**

![](H:/CENG 355/FarmBotSystem2.png)

![](H:/CENG 355/FarmBotSystem3.png)

The hardware component for FarmBot that I have are:

-   Raspberry pi 3 – It is used to receive data from FarmBot and send it to the
    Arduino

-   Arduino mega 256 – It is used to control the bi-polar stepper motor

-   Sensor Hat (light and temperature) – It is used to receive data about light
    and temperature from surrounding.

-   Bi-polar Stepper motor – It controls the movement of the FarmBot

**System overview**

FarmBot will be able to perform the following task:

-   Monitor the temperature around the plant,

-   Provide light to the plant,

-   Check the moisture of the soil,

-   Also, check the pH content of soil.

**References**

These are the references I am going to use for the duration of this project,
though if I come across other references I will add them.

[1] Agricultural robotics [TC Spotlight] - IEEE Xplore Document. (2009, December
11). Retrieved January 16, 2017, from
http://ieeexplore.ieee.org/document/5306920/

[2] Robot Farmers: Autonomous Orchard Vehicles Help Tree Fruit Production - IEEE
Xplore Document. (n.d.). Retrieved January 16, 2017, from
http://ieeexplore.ieee.org/document/7059344/

[3] Raspberry Pi 3 Complete Starter Kit - 32 GB Edition. (n.d.). Retrieved
January 16, 2017, from https://www.canakit.com/raspberry-pi-3-starter-kit.html

[4] Upton, Liz. (2015, August 28). Raspberry Pi colocation [Online]. Available:
http://raspberrycolocation.com/

**Database Work Breakdown**

Currently, I only have a local database for my FarmBot project. The database
stores the plant number, date, and name locally. Once the app is deleted the
users will lose access to all their data.

I plan on getting a server to so all users data can be stored in the cloud and
can be accessed by them at any time

**Application and work breakdown**

FarmBot is going to be more economical and ecofriendly unlike other agricultural
equipment being used. It incorporates precision farming, which happens to be a
concept based on observing, measuring and responding to inter and intra-field
variability in crops. The device is going to be constructed be the FarmBot
company, it is going to be made of an Arduino Mega 2650, Raspberry Pi 3, Sensor
hat (which can read temperature, light, and soil condition), and Bi-polar
stepper motor.

I plan on first tightening a pulley to my bi-polar, then create a pulley system
with the motor and a case.

**Web and work breakdown**

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

I plan on connecting FarmBot’s app with raspberry pi, so that users can be able
to send data to it.
