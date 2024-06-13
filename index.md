# Ball Tracker Robot
From glowing bugs to AI robots, my journey at BlueStamp has been filled with adversity and opportunity. The Ball Tracker Robot works by detecting a red ball using AI to determine its next course of action


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Eric S | Lowell HS | Electrical Engineering | Incoming Sophomore

![Headstone Image](logo.svg)
  
# Final Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y(https://www.youtube.com/embed/NTk1sGW9OV4?si=9ZicSQZY8JYFDKma)" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# First Milestone

For my first milestone, I have decided to finish setting up the hardware required to operate my robot. Essentially, the chassis, or the clear glass with wheels attached to it strings together the other parts, allowing the robot to actually move. The Arduino and Raspberry Pi, which are both situated on top of the chassis, allow electricity to spread to other parts and receive code. Combined with the HC-SR04 sensors on the front, my robot will eventually be able to detect other objects and move accordingly. As for obstacles, one I have faced is the instructions manual for the chassis, which was poorly designed. The instructions stated to put screws a certain way, but that would be impossible because there wasn't enough room to use a nut to keep it in place. However, I solved this problem by simply changing the direction the screws faced. As for the future, I hope to start my code soon.


# Starter Project
<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


My starter project is the Weevil Eyes, which is a light-detecting bug that glows depending on the surrounding light. If the environment is dark, then the lights glow up. For this project, there weren't any big challenges due to the lack of coding and complex steps. Essentially, the bug works by sensing the surrounding light with a sensor at the bottom. If there is light, that signal will go towards the transistor, which is like a switch. When there is light, the transistor will make sure that the LEDs do not light up. However, if there isn't light, the transistor will send electricity to the resistors, which resist electricity to ensure that the LEDs are not fried. And as electricity goes through the resistors and towards the LEDs, the LEDs then illuminate.

# Schematics 

# Code 

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

# Materials Used

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Raspberri Pi 4 Model B | Used to control the robot and to write code | $61.75 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |](https://www.amazon.com/Raspberry-Model-2019-Quad-Bluetooth/dp/B07TC2BK1X?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&smid=A2QE71HEBJRNZE&th=1)
| Raspberry Pi Camera Module | Video capture | $14.99| <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| L298N Driver Board | Drives the wheels forward and backwards | $8.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> 
| Motors and Board Kit | Holds the hardware together like a frame | $12.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Powerbank | Power supply for Raspberry Pi | $19.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| HC-SR04 Sensors | Allows the robot to see obstacles | $8.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| HDMI to Micro HDMI Xable | Connects pi to the monitor | $8.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Video Capture Card | Allows for display on laptops | $14.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| SD card reader | What the item is used for | $4.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Wireless Mouse and Keyboard | Used to operate Rasp pi | $19.98 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Basic Connections Component Kit | What the item is used for | $11.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Female to Female Jumper Wires | Used to connect parts to others | $7.98 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Soldering Kit | Used for motor connections | $14.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
