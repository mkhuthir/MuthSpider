# MuthSpider

![MuthSpider](https://s3-eu-west-1.amazonaws.com/muthspider/img/MuthSpider.png)<br>
==========
   
   A hexapod spider robot controlled by [Robotis CM-700 controller](http://support.robotis.com/en/product/auxdevice/controller/cm700_manual.htm), motorized by twenty [Robotis Dynamixel AX-18A servos](http://support.robotis.com/en/product/dynamixel/ax_series/ax-18f.htm), and one [Robotis AX-S1 integrated sensor](http://support.robotis.com/en/product/auxdevice/sensor/dxl_ax_s1.htm) mounted on its head. The robot frame is a slightly modified TrossenRobotics ABS PhantomX kit.
 

#Robot Controller (CM-700):

There are many options of robotic controllers in the market and it is a great fun to try it all. Initially I started this spider project using the 1st version of TrossenRobotics Arbotix controller with the open source software from the same company. Then I tried the ROBOTIS OpenCM9.04 open source controller along with its Arduino like IDE. Finally, I picked ROBOTIS CM-700 controller along with ROBOTIS RoboPlus Software. I’m not sure how long I will keep using it.

![CM-700-1](https://s3-eu-west-1.amazonaws.com/muthspider/img/CM700-full.png)

What I like about CM-700 is its compact design, the low-power 8-bit AVR RISC-based microcontroller (ATMEL ATMEGA2561) which is widely used in many applications including Arduino boards, its big number of ports, and the very user friendly RoboPlus software.


![CM-700-2](https://s3-eu-west-1.amazonaws.com/muthspider/img/CM700-parts.png)

**Controller Specfications:**

* **MCU : ATMEL ATMega2561**
* **Working Temperature :** -5℃~70℃*
* **Weight :** 37.3g
* **Working Voltage:**
   * Allowed Range : 7V ~ 35V
* **Current:**
   - Consumed Current When idle  : 40mA
   - Exterior I/O Maximum Current : 0.9A
   - Overall Maximum Current : 10A (Fuse)
* **Internal I/O Device**
   - Button : 2 sets (Reset 1, Start 1)
   - Temperature Sensor : 1
   - Voltage Sensor : 1
* **External I/O Device**
   - OLLO 5 pin I/O Port : 6
   - 3-Pin Connector TTL Communication : 4
   - 4-Pin Connector RS-485 Communication : 5


#Robot Motors (AX-18A):

 
![AX-18A](https://s3-eu-west-1.amazonaws.com/muthspider/img/AX-18A.png)
 
#Robot Sensors (AX-S1):

 
![AX-S1](https://s3-eu-west-1.amazonaws.com/muthspider/img/AX-S1.png)

#Repository Contents

* **/Docs** - Project Related documentations.
* **/RoboPlus Motion** - Motion Files generated using Robotis RoboPlus Motion 1.0.
* **/RoboPlus Task** - Task Files generated using Robotis RoboPlus Task 1.0.

#Version History

* Initial version (work in progress).


#License Information

The hardware is released under [Creative Commons Share-alike 3.0](http://creativecommons.org/licenses/by-sa/3.0/).  
All code is open source so please feel free to do anything you want with it under the [Beerware license](http://en.wikipedia.org/wiki/Beerware).
