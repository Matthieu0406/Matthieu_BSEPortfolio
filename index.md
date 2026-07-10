# Gesture Controlled Robot
My project is a gesture controlled rover which uses an accelerometer to steer. It will include a crash prevention system and a robotic arm that uses hand gestures to operate
<!--You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions-->


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Matthieu M | King's School Nad Al Sheba | Mechanical Engineering | Incoming Junior

<!--**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**-->

![Headstone Image](logo.svg)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

# First Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project

# Starter Project


<iframe width="560" height="315" src="https://www.youtube.com/embed/I2zmZ7ad-JA?si=v72tMYZKy2vI-kmm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


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
