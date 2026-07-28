# Gesture Controlled Robot
My project is a gesture controlled rover which uses an accelerometer to steer. It will include a crash prevention system and a robotic arm that uses hand gestures to operate
<!--You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions-->


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Matthieu M | King's School Nad Al Sheba | Mechanical Engineering | Incoming Junior

<!--**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**-->

![Headstone Image](['Matthieu M.jpeg'](https://github.com/Matthieu0406/Matthieu_BSEPortfolio/blob/gh-pages/Matthieu%20M.jpeg))
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone: Electronics wiring, Code and Hand controller

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/peg865jYkdk?si=Pbq0_7J3rtQGzmYr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

OVERVIEW

For my second milestone, the focus was connecting all electronic components and bringing the car under control using a custom hand-held controller. By integrating an MPU-6050 accelerometer and gyroscope onto a wearable glove or hand controller, I implemented tilt-based gesture control to drive and steer the vehicle wirelessly based on hand movements.

DESIGN AND DEVELOPMENT

Hand Controller Setup: Built a custom hand controller incorporating an MPU-6050 sensor to detect physical hand orientation (pitch and roll).

Gesture Mapping Software: Developed embedded software to translate tilt angles into movement commands—tilting forward drives the car ahead, tilting back reverses, and leaning left or right steers the car.

System Integration: Wired the Arduino to the L298N motor driver and established communication between the hand controller inputs and motor output controls.

CHALLENGES

Accelerometer Data Drops (I2C Bus Lockup): The MPU-6050 sensor on the hand controller repeatedly got stuck or failed to communicate over the I2C bus (0x68 address missing), requiring extensive multimeter testing, voltage checking, and troubleshooting.

Gesture Calibration & Smoothing: Motion data from hand movements was initially noisy, causing the car to jump or jerk uncontrollably; this required filtering input values to ensure smooth driving responses.

SKILLS DEVELOPED

Gesture & Sensor Integration: Learned how to process 3-axis accelerometer and gyroscope data to read hand orientation in real time.

Advanced Debugging: Gained experience troubleshooting I2C protocol issues, signal thresholds, and logic-level voltage drops using a multimeter and diagnostic sketches.

Motor & Motion Control: Mastered converting continuous physical motion inputs into discrete motor driver logic commands.

PLAN FOR COMPLETION

Milestone 3: Add final modifications, refine wireless hand controller range, optimize gesture thresholds, and complete full vehicle chassis integration.

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/inS2sAPzMKU?si=dW4qDtg-NDgFor9E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

OVERVIEW
My main project is an autonomous/Bluetooth-controlled robot car powered by an Arduino microcontroller. For my first milestone, the focus was constructing the physical foundation of the vehicle by assembling the aluminium chassis, mounting the DC gear motors, attaching the wheels and other vital components like the micro controller and L298N H-bridge

DESIGN AND DEVELOPMENT
Chassis Construction: Mounted the 4 DC motors onto the main aluminium plate using screws and nuts.

Drivetrain Setup: Attached the wheels directly to the motor and screwed it in with a servo screw.

Component Layout: Pre-planned the mounting locations on the chassis for the battery holder, motor driver board (L298N/L293D), Arduino controller, and sensor modules to ensure balanced weight distribution and ample space for wiring and other potential components.

CHALLENGES
Motor Alignment: Aligning the motors and mounting brackets straight was tricky; if they are slightly crooked, the car drags or pulls to one side when driving forward.

Tiny Hardware & Tight Spaces: Threading the tiny nuts and bolts through the aluminium slots required patience and precise hand tools, taking extra time to ensure nothing was over-tightened and cracked.

Hardware Layout: Planning the layout for the hardware was challenging becuase I had a lot of fairly large componentents and very little space.

SKILLS DEVELOPED
Mechanical Assembly: Learned how to build and align multi-wheel robotic drivetrains.

Hardware Planning: Understood spatial layout planning for electronics, power supplies, and wiring routing on a small chassis.

Tool Usage: Gained practical experience using small screwdrivers, pliers, and mounting hardware effectively.


# Starter Project


<iframe width="560" height="315" src="https://www.youtube.com/embed/I2zmZ7ad-JA?si=dT0UwxztJV6SGUgC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

OVERVIEW
- My starter project is a retro handheld videogame console built around a microcontroller. It features 2 8x8 pixel screen which creates a simple and engaging platform for gaming. The primary focus of this project was to improve my soldering skills.

DESIGN AND DEVELOPMENT
- The console integrtes a microcontroller, two 8x8 LED screens, a buzzer ,AA batteries and physical control buttons. The embedded softare was developed to generate sound effects, display graphics and execute game logic. Meticulus optimization was required to guarentee smooth gameplay considering the limited processing power.

CHALLENGES
- The main challenge was the assembly and soldering. Before this I had never soldered anything, so it hard to solder the smaller components.
- Initially I messed up the assembly of the outer case. I used the wrong screws and attached the case in the wrong order. It took 30mins to an hour to fix this issue

SKILLS DEVELOPED
- I learnt how to solder and got pretty good at it.
- I learnt about micro controllers and other basic components.
- Digital electronics and integrating hardware.
- I learned how to optimize software for limited resources
  

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

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
<!--Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs.-->

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Arduino UNO R3 | Main microcontroller used to process inputs and control the robot's components | $27.60 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Arduino Nano (Knockoff) | Compact microcontroller used in the handheld controller | $6.99 | <a href="https://www.amazon.com/s?k=Arduino+Nano+V3.0+ATmega328P+knockoff"> Link </a> |
| MPU6050 IMU (6 Degrees of Freedom) | Measures acceleration and rotation to detect hand movements and gestures | $7.99 | <a href="https://www.amazon.com/s?k=MPU6050+6DOF+gyroscope+accelerometer"> Link </a> |
| Half Size Solderless Breadboard | Used for building and testing circuits without soldering | $5.99 | <a href="https://www.amazon.com/s?k=half+size+solderless+breadboard"> Link </a> |
| HC-05 Bluetooth Module x2 | Provides wireless communication between the handheld controller and robot | $9.99 | <a href="https://www.amazon.com/s?k=HC-05+Bluetooth+module"> Link </a> |
| Male/Male Jumper Wires | Used to connect components on breadboards during prototyping | $6.99 | <a href="https://www.amazon.com/s?k=male+to+male+jumper+wires"> Link </a> |
| Male/Female Jumper Wires | Used to connect modules and sensors to the microcontrollers | $6.99 | <a href="https://www.amazon.com/s?k=male+to+female+jumper+wires"> Link </a> |
| 12V DC Motor | Provides movement and power for the robot wheels | $12.99 | <a href="https://www.amazon.com/s?k=12V+DC+gear+motor"> Link </a> |
| L298N H-Bridge Motor Driver | Controls the speed and direction of the DC motors | $8.99 | <a href="https://www.amazon.com/s?k=L298N+motor+driver"> Link </a> |
| 9V Battery | Provides portable power for electronic components | $6.99 | <a href="https://www.amazon.com/s?k=9V+battery"> Link </a> |
| USB-C Powerbank | Provides rechargeable power supply for the robot system | $19.99 | <a href="https://www.amazon.com/s?k=USB+C+power+bank"> Link </a> |
| Half Size Breadboard | Allows temporary circuit connections for testing electronics | $5.99 | <a href="https://www.amazon.com/s?k=half+size+breadboard"> Link </a> |
| Robot Car Chassis | Provides the physical frame, wheels, and structure for the robot | $14.99 | <a href="https://www.amazon.com/s?k=robot+car+chassis+kit"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
