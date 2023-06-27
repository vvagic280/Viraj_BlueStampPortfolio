# Infrared Remote Controlled Car with Ultrasonic Sensor
Discover the remarkable adventure of my robot-controlled car, brought to life with an Arduino and a wide combination of components. From overcoming technical challenges to the construction of the robot, this project has been an insightful experience. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Viraj V | Dougherty Valley High School | Mechanical Engineering | Incoming Junior

![Headstone Image](IMG_3642.thumbnail.jpg)
  
# Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Second Milestone
Since my previous milestone, I have worked on technical aspects of my project, including software and code integrated into the RC Car. I was able to upload code for the IR Remote to work with my car, and get it to move in the direction I want it to using the remote. I did this by having the car move in the direction I want it to by clicking the control once and letting it keep moving with no delay until I command it to either stop in place, or click a different control to move in a different direction. This way, I have the ease of not needing to constantly hold down the button and just let it continue to move in the direction I want it to until I click the "stop" command button or a different direction. A challenge I faced was the first code I found online didn't work like I wanted it to and just kept repeating the "stop" command repeatedly even when I didn't click any controls on the remote. I overcame this by editing some of the code and integrating some code from my previous upload of the IR Remote and got it to respond to the remote and get the motors running.

<iframe width="560" height="315" src="https://www.youtube.com/embed/vc1ye0t6fUM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# First Milestone
My project is the RC Car and this is my first milestone. So far, I have completed piecing together the base of my project and have the overall hardware for the wires all plugged into the Arduino UNO. Some key components for this project include an ultrasonic sensor located in the front of the car for obstacle avoidance features, four motors for the tires to run, an Arduino UNO for plugging in all the components, a reciever; later used for the remote control, and a USB input to later integrate code into my project. A challenge I faced was not being able to plug in the camera; located on the top of the car, into the serial port on the arduino UNO because unfortunately with this chip I cannot plug both the camera, and the USB for uploading code, at the same time. My plan to complete this project is to get the motors up and running with the given IR (Infarred Remote) Control from the kit and get the ultrasonic sensors to work and avoid any objects in its path.  

<iframe width="560" height="315" src="https://www.youtube.com/embed/lkt41rrJCsg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Schematics 
![Headstone Image](Funky_Habbi.jpg)

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

# Bill of Materials
| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Elegoo Smart Robot Car | Project Kit for RC Car | $79.99 | <a href="https://www.amazon.com/ELEGOO-Tracking-Ultrasonic-Intelligent-Educational/dp/B07KPZ8RSZ"> Amazon Link </a> |
|:--:|:--:|:--:|:--:|

# Outside Resources
- [Example Code For IR Remote](https://dronebotworkshop.com/elegoo-smart-robot-car-part-2/#Infrared_Remote_Car_Control)
- [SunFounder Ultrasonic Module](https://docs.sunfounder.com/projects/3in1-kit/en/latest/car_project/car_ultrasonic.html)
- [Sparkfun Motor Test Run/Library](https://learn.sparkfun.com/tutorials/sik-experiment-guide-for-the-arduino-101genuino-101-board/experiment-12-using-the-motor-driver)
