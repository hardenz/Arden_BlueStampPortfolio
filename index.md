# Hexapod
My main project is the hexapod, which is a robot with 6 legs. The hexapod is made up of various different acrylic parts, and is controlled with a control board in the middle of the main chassiss, and can be controlled by either plugging the robot into a computer or with a WLAN module that can be installed in the robot. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Arden Z | Fremont High School |  | Incoming Sophomore

<!---
**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)

-->
  
# Final Milestone
For my final milestone, I completed my hexapod, which can be controlled with a controller using a module on the hexapod and a module on the controller. The hexapod can also be controlled using a phone or a computer wirelessly, using a wifi module also installed on the hexapod. I installed the battery on top of the robot using velcro so it wouldn't drag behind the hexapod when moving. In order to control the hexapod using the controller, I uploaded the controller firmware onto the controller using arduino ide, and then recallibrated the hexapod legs. I then installed the controller module onto the controller and the hexapod. One issue I ran into during this step was that the port for the controller module on the hexapod was melted, and it was missing half of the holes. To solve this issue, I used a dremel tool to drill the missing holes where the port had melted back into the port in order to plug the module in. 


# Second Milestone
For my second milestone, I finished calibrating each of the 6 legs of my hexapod. Since my last milestone, I unplugged each servo and then plugged them in again to their respective correct spot on the control board. I then tied up each servo according to their leg with cable tidyers in order to organize them. I installed the bottom part of the main chassiss, and then plugged the control board into my computer to start the calibration process. I placed the hexapod on the calibration graph that came with the parts, and started calibrating each leg individually using the control app. One challenge I faced during this process was that the instructions were not very clear on what the height of each leg should be during the calibration process. When the robot is in calibration mode, the height of each leg is lower than in installation state, so in start, I calibrated each leg to be the same height as in the installation process. Howeverm, this was not the correct step, so I had to restart the calibration process with the correct height. 

# First Milestone
For my first milestone, I finished installing and assembling all the physical parts of the hexapod. My project is made up of different acrylic pieces, servos, and a main control pod. The acrylic pieces fit together in different ways to make up the legs and main body of the hexapod. For my milestone, I screwed together all the servos to their required acrylic pieces, and then connected the acrylic pieces together to create the required parts of the robot. I then uploaded firmware onto the main control board. I assembled all the acrylic parts onto the main body of the hexapod, and plugged all the servos into the control board. Some challenges I have faced so far is that some servos do not work, and the positioning of some legs are not correct. I plan to solve these by replacing some servos, and fix the orientation of the legs in the calibration step in the future. I plan to complete my project by continuing to follow the instructions and fixing any problems that come up. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/kaPv2Ap6h-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<!---
# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

-->

<!---
# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```
-->

# Bill of Materials
| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| FREENOVE Hexapod Kit | Hexapod Components | $129.95 | [Link](https://www.amazon.com/Freenove-Raspberry-Crawling-Detailed-Tutorial/dp/B07FLVZ2DN?th=1/)

# Starter Project
My starter project is the useless box. The box works by flipping a switch, which switches a motor inside the box. There is an arm attached to the motor, which pushes a flap open at the top of the box, and then pushes the switch. The motor then retracts the arm back into the box.

[Link](http://www.spikenzielabs.com/Catalog/useless-machine/the-useless-machine-kit-no-soldering-required/)
