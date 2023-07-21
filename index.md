
My main project is the hexapod, which is a robot with 6 legs. The hexapod is made up of various different acrylic parts, and is controlled with a control board in the middle of the main chassiss, and can be controlled by either plugging the robot into a computer or with a WLAN module that can be installed in the robot. The hexapod can perform various functions, including crawling, twisting, and tilting. It can also be controlled with an included controller, using a control module installed on both the controller and the control board of the hexapod. 

[Guide](https://github.com/Freenove/Freenove_Hexapod_Robot_Kit)


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Arden Z | Fremont High School | Engineering | Incoming Sophomore

![Picture](/Arden_BlueStampPortfolio/docs/IMG_9309.jpeg =50x50)




# Final Milestone Modification

<iframe width="560" height="315" src="https://www.youtube.com/embed/x15ACGFqruA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my final milestone and modification, I built a robot arm and mounted it onto my hexapod. The robot arm is controlled with an arduino nano, which is mounted on a nano shield where all the servos and controls are plugged into. There are 4 servos on the robot arm, which each controls a different part of it. The robot arm itself is made up of acrylic parts, and is mounted on a baseplate. While constructing the robot arm, some of my acrylic parts snapped and broke, so I replaced them with the same parts from a spare robot arm. The code to control the arm is included in the instructions, so all I had to do was upload it onto the arduino nano and the robot arm could be controlled with the two included controllers. 
  After I finished constructing the robot arm, I worked on mounting the arm onto the hexapod and combining the controls for the arm and the hexapod. I used standoffs and screws to mount the arm on the hexapod, but the standoffs I had were not long enough, so I designed new ones in Onshape and 3d printed them. To mount the arm using screws, I removed the arm and controller module off of the baseplate and drilled holes where the screws would go, and then reinstalled the arm and module. I used the standoffs and screws to mount robot arm onto the hexapod using the screw holes I drilled. To combine the controls for both, I designed a mount for the hexapod controller and robot arm controller in Onshape and 3d printed them. One problem I ran into during this process was that the design was too big to be printed at once, so I cut it into two sections and printed it seperately, then superglued it together. I extended the wires of the robot arm controller so it could be controlled from a farther distance once I mounted both controllers together.


# Third Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/SFgJRhP5xGY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my final milestone, I completed my hexapod, which can be controlled with a controller using a module on the hexapod and a module on the controller. The hexapod can also be controlled using a phone or a computer wirelessly, using a wifi module also installed on the hexapod. I installed the battery on top of the robot using velcro so it wouldn't drag behind the hexapod when moving. In order to control the hexapod using the controller, I uploaded the controller firmware onto the controller using arduino ide, and then recallibrated the hexapod legs. I then installed the controller module onto the controller and the hexapod. One issue I ran into during this step was that the port for the controller module on the hexapod was melted, and it was missing half of the holes for the module pins. To solve this issue, I used a dremel tool to drill the missing holes where the port had melted back into the port in order to plug the module in. 


# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/-hPhnmBrBKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my second milestone, I finished calibrating each of the 6 legs of my hexapod. Since my last milestone, I unplugged each servo and then plugged them in again to their respective correct spot on the control board. I then tied up each servo according to their leg with cable tidyers in order to organize them. I installed the bottom part of the main chassiss, and then plugged the control board into my computer to start the calibration process. I placed the hexapod on the calibration graph that came with the parts, and started calibrating each leg individually using the control app. One challenge I faced during this process was that the instructions were not very clear on what the height of each leg should be during the calibration process. When the robot is in calibration mode, the height of each leg is lower than in installation state, so in start, I calibrated each leg to be the same height as in the installation process. However, this was not the correct step, so I had to restart the calibration process with the correct height of the legs and recalibrate the position of each of them. 

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/kaPv2Ap6h-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my first milestone, I finished installing and assembling all the physical parts of the hexapod. My project is made up of different acrylic pieces, servos, and a main control pod. The acrylic pieces fit together in different ways to make up the legs and main body of the hexapod. For my milestone, I screwed together all the servos to their required acrylic pieces, and then connected the acrylic pieces together to create the required parts of the robot. I then uploaded firmware onto the main control board. I assembled all the acrylic parts onto the main body of the hexapod, and plugged all the servos into the control board. Some challenges I have faced so far is that some servos do not work, and the positioning of some legs are not correct. I plan to solve these by replacing some servos, and fix the orientation of the legs in the calibration step in the future. I plan to complete my project by continuing to follow the instructions and fixing any problems that come up. 


# Schematics 
![Hexapod Control Board Schematic](/Arden_BlueStampPortfolio/docs/hexapod schematic.png)

[Link to Schematic](https://github.com/Freenove/Freenove_Hexapod_Robot_Kit/blob/master/Hardware/FNM0019B_Freenove%20Crawling%20Robot%20Controller%20V3.1_Schematic.pdf/)

This is the schematic for the hexapod main controller

# Code
[Link to Code](https://github.com/Freenove/Freenove_Hexapod_Robot_Kit/tree/master/ProcessingApp/)

This is the code to control the hexapod

# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| FREENOVE Hexapod Kit | Hexapod Components | $129.95 | [Amazon Link](https://www.amazon.com/Freenove-Raspberry-Crawling-Detailed-Tutorial/dp/B07FLVZ2DN?th=1/) |
| LK Cokoino Robot Arm Kit | Robot Arm Components | $49.99 | [Amazon Link](https://www.amazon.com/LK-COKOINO-Compliment-Engineering-Technology/dp/B081FG1JQ1/) |

# Starter Project
<iframe width="560" height="315" src="https://www.youtube.com/embed/wo1IoIR5G-k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

My starter project is the useless box. The box works by flipping a switch, which switches a motor inside the box. There is an arm attached to the motor, which pushes a flap open at the top of the box, and then pushes the switch. The motor then retracts the arm back into the box.

[Link to Project](http://www.spikenzielabs.com/Catalog/useless-machine/the-useless-machine-kit-no-soldering-required/)
