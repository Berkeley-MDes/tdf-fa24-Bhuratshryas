# Hello,

<img align="right" width="200" alt="Shryas Bhurat Portrait" src="assets/shryasbhurat.jpeg">

I'm [**Shryas Bhurat**](https://www.shryasbhurat.com), an **Engineer**, **Designer**, & **Entrepreneur**.

Incredibly passionate about merging:
- Science
- Design
- Technology
- Entrepreneurship

To improve the quality of life.


# TDF Weekly Progress
[week 1](README.md#week-1-personalizing-my-new-berkeley-home) , 
[week 2](README.md#week-2-Exploring-Rhino-Grasshopper-and-3D-Printing-this-week) ,
[week 3](README.md#week-3-putting-all-skills-into-work) ,
[week 4](README.md#week-4-moving-towards-building-interactive-tools) ,
[week 5](README.md#week-5-playing-with-photon) 

---------------------------------------------------------------------------------------------------------

# Week 5: Playing with Photon
## Week of 09/30/2024

### Reflections

This weekend, I worked on playing with Photon, to connect it to internet, add some electronics components on a bread board and play with bliking a bulb. 

I first began with connecting my photon with the home internet, it was easy to follow to tutorials to get it connected to the internet.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="60%" alt="Connecting to Home Network" src="assets/Connecting to home network.png">
</div>

Then I ran few codes on printing Hello world in different ways, with different delays to understand on how to flash photon software, what happens during compilation, how to look at serial monitor, go deeper into delays and why they are important, below are my iterations.

1. Printing Hello world.
2. Printing Hello world, but one word in a line.
3. Priting Hello world, with different delay rates.
   
<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="33%" alt="Printing Hello World" src="assets/Hello World.mp4">
    <img width="33%" alt="Printing Hello world but one word in a line" src="assets/Hello World, one word in a line.mp4">
    <img width="33%" alt="Priting Hello world with different delay rates" src="assets/Hello World.mp4">
</div>


### Diagrammatic Analysis of a Microelectronics Project

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="33%" alt="Micro Electronics Circuit" src="assets/microelectronics_intro.png">
    <img width="33%" alt="Micro Electronics Setup" src="assets/Microelectronics Setup.jpeg">
    <img width="33%" alt="Micro Electronics Run" src="assets/Microelectronics Run.mp4">
</div>

Then I put all that I learnt about resisters, photon, delays, flashing, connecting it to internet and bread boards to blink a bulb with 3 volts of voltage using the diagram shared on how to make connections, I also had to add few resistors so that the current flow can be reduced suitable for both bulb and the button added to change the delay randomization for the software.

The images below show button pressed to change the speed of the delay (300 ms - 1000 ms & 30 ms to 300 ms), blinking fast and blinking slow based on button pressed to change the speed within the range.
<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="33%" alt="Button Pressed shown on Terminal" src="assets/Button Pressed.mp4">
    <img width="33%" alt="Blink Slow based on lower range on periodicity" src="assets/Blink Slow.mp4">  
    <img width="33%" alt="Blink Fast based on higher range on periodicity" src="assets/Blink Fast.mp4">    
</div>

### Speculations

I think this will be a very useful skill and will help me to work on projects that have hardware aspects to it. I look forward to playing more with photon, to build a interactive tool that can take data realtime in a hardware setting and transfer it to the software aspects, so that we can learn from the tools/wearable that we use, similar to smart watches and digital devices.


---------------------------------------------------------------------------------------------------------

# Week 4: Moving towards building interactive tools
## Week of 09/23/2024

### Reflections

I started by reflecting on my journey, on what I use in daily life, and how each object shares data and works together. There are a lot of feedback mechanisms built in the systems currently that I realized today as I noticed the interactions of digital systems in sharing data to make our lives easier. 

### Devices & tools that I use every day.

1. Smart Phone
2. Laptop
3. Smart Watch
4. Smart Speaker
5. Email
6. Calendar
7. Wallet
8. Credit Card
9. Bank Account
10. Google Meet
11. Online Shopping Applications
12. Movie Streaming & Video Streaming Services
13. Gaming Applications
14. Refrigerator
15. Smart Lights
16. GPT

### Diagrammatic Analysis

- Calendar, Gmail, and Video Conferencing are linked to each other and constantly transfer data.
- Wallet, Credit Card, and banking applications are linked to each other and constantly transfer data.
- Laptop is linked with Bluetooth or wireless speakers at home, it is also linked to wireless mouse and keyboard to transfer and receive data.
- Smart phone and smart watch are linked together to track health goals, messaging, calls and other application-oriented activities that tend to become invisible with proper feedback loops.
- Smart phones are also linked to refrigerators, smart light and thermostats to make home settings more friendly and interactive.
- Social media applications like instagram & whatsapp are linked to eachother, to learn from users data and show us advertisements on the same.

Here is a diagram to show how things relate to each other with feedbacks that they tend to transfer to each other.

  
<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="200%" alt="Custom Keychain" src="assets/Digital Ecosystems.png">
</div>

### System Interaction put to action

#### This week I also attended a AI Hackathon, focused towards health with SunQ and Josh from the MDes Cohort and we ended up building a interaction system between phone call, llm's, human dispatchers, hospitals and ambulance providers.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="60%" alt="Custom Keychain" src="assets/IMG_7711.jpg">
</div>

- problem: every minute matters in an emergency scenario and response can be slowed down by manual operation and human error
- solution: an ai voice workflow to help automate triaging and response 
- Link to the video: https://youtu.be/Zw503GZLikM

### Map for systems interacting for the product we built during the hackathon

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="60%" alt="Custom Keychain" src="assets/Rapid Response.jpg">
</div>

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="60%" alt="Custom Keychain" src="assets/Interactive System for Rapid Response.jpeg">
</div>


This is the framework that helped me understand how machines interact with each other and transfer data to optimize processes.

### Speculations

I feel the world is getting more and more connected with data transfer from one application to another, all the Google applications are linked to each other. Some connect to other applications using application protocol interface, to transfer data. We are always communicating with the world using the internet and it's getting more and more every day. 

With AI playing a huge role in the current world, we will soon see a world where all these interfaces become even more invisible. The communication layer is still invisible but sooner we will see a world where the interface layer becomes invisible too.

---------------------------------------------------------------------------------------------------------

# Week 3: Putting all skills into work #
## Week of 09/16/2024

### Reflections
I want to push myself to build a model from scratch and make use of my skillsets to build something that solves a real problem for me and has a real use case. As you know I moved to Berkeley and am setting up my room, my charging area is currently messed up with too many things moving, and too many cables, it does not look elegant at all, so I wanted to build a stand that can hold my phone and also my I watch and charge them at once.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="32%" alt="Custom Keychain" src="assets/WhatsApp Image 2024-09-18 at 21.47.49 (1).jpeg">
    <img width="32%" alt="Custom Keychain" src="assets/WhatsApp Image 2024-09-18 at 21.47.49.jpeg">
    <img width="32%" alt="Custom Keychain" src="assets/Group 5.png">


</div>

#### To make it easy for me to utilize the resource while making it look elegant.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="32%" alt="Custom Keychain" src="assets/SCR-20240919-beds.png">
     <img width="32%" alt="Custom Keychain" src="assets/SCR-20240919-bdzg.png">
</div>

#### Youtube Video
https://www.youtube.com/watch?v=eQastMoem7A (fun video to watch)

I also expanded my work in video editing and this video shows the overall things that I worked on.

#### Speculations

I expected everything to work fine for the first instance itself, but I had to reiterate it and learn a little more about tolerances with 3d printing.


---------------------------------------------------------------------------------------------------------

# Week 2: Exploring Rhino Grasshopper and 3D Printing this week #
## Week of 09/07/2024

Rhino seems like an interesting software to build things as it is parametric and things can be edited quite quickly because of this. I wanted to make the phone stand for my phone dimensions so that I could keep it comfortably on my study table.

Here's how it went like:

My Understanding of Parametric Modeling

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="50%" alt="Custom Keychain" src="assets/Rhino Modelling.png">
</div>


I tried to edit the parameters to the iPhone XR dimensions
<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="32%" alt="Custom Keychain" src="assets/Param1.png">
    <img width="32%" alt="Custom Keychain" src="assets/Param.png">
</div>

However, it did not work at the first instant as the base thickness was limited and the CG was going outside the stability criteria, I hence had to change the angle of the phone to make it more stable.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="32%" alt="Custom Keychain" src="assets/Sizedifference.png">
    <img width="32%" alt="Custom Keychain" src="assets/Assemnotgood.png">
</div>

It worked, the phone was more stable and I could bake the results instantly & then I tried to replace the base with a cylinder.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="32%" alt="Custom Keychain" src="assets/Assemgood.png">
    <img width="32%" alt="Custom Keychain" src="assets/phonestand3dprinted.png">
     <img width="32%" alt="Custom Keychain" src="assets/Cylinderinsteadofsphere.png">
</div>

They then created a 3D file to print the output so that I could use it.

I also tried to make a model from scratch using Grasshopper, to keep things near my bed sorted.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="32%" alt="Custom Keychain" src="assets/TableOnRhino.png">
    <img width="32%" alt="Custom Keychain" src="assets/3DPrintingtable.png">
     <img width="32%" alt="Custom Keychain" src="assets/BoxforBed.jpeg">
</div>

It was fun to play with parameters and very quick iterations.







---------------------------------------------------------------------------------------------------------

# Week 1: Personalizing My New Berkeley Home #
## Week of 09/05/2024

After moving to Berkeley, I moved to a new home and wanted to make it more personal space, hence this week I worked on mini projects for my study table and home.

## DIY Projects

### Cool Pencil Stand

I made a cool pencil stand to organize my writing tools and add a unique touch to my study area. This custom-made stand serves a practical purpose and reflects my style using 3D Printing.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="32%" alt="Cool Pencil Stand" src="assets/holdercad.jpeg">
    <img width="32%" alt="Cool Pencil Stand" src="assets/holder printing.jpeg">
    <img width="32%" alt="Cool Pencil Stand" src="assets/Holder Picture">

</div>


### Custom Keychain

For my new home keys, I created a custom keychain. This personalized accessory helps me easily identify my house keys and adds a bit of flair to my everyday items using 3D Printing.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="32%" alt="Custom Keychain" src="assets/keychain printing.jpeg">
    <img width="32%" alt="Custom Keychain" src="assets/keychain printing 2.jpeg">
    <img width="32%" alt="Custom Keychain" src="assets/keychain.jpeg">
</div>


### Cal Logo for My Table

I made a Cal Logo for my table to show my connection to my new academic community. This decorative piece proudly displays my affiliation with the University of California, Berkeley, and adds a touch of school spirit to my study space using Laser Cutting.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="32%" alt="Cal Logo for My Table" src="assets/cal cutting.jpeg">
    <img width="32%" alt="Cal Logo for My Table" src="assets/Cal.jpeg">

</div>

## Impact

These DIY projects have helped me transform my new living space into a more personalized environment. By adding these custom touches, I've begun to make my new Berkeley home feel more like my own.

In the future, I will try to merge technology tools to build something that can solve my problems in the quickest way possible.

<img width="600" alt="Study Table" src="assets/Study Table">

---

## Quick Links ##

- [TDF Wiki](https://github.com/Berkeley-MDes/24f-desinv-202/wiki) - the ultimate source for truth and information about the course and assignments
- [Google Drive Folder](https://drive.google.com/drive/u/0/folders/1DJ1b6sSDwHXX6NRcQYt10ivyQSgU0ND6) - slides and other resources
- [bCourses](https://bcourses.berkeley.edu/courses/1537533) - where the grading happens
- [Weekly Submission Form]( https://tinyurl.com/DESINV202-PersonalReflections) - where reflection happens

