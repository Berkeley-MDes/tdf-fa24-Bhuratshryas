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
    <img width="33%" alt="Connecting to Home Network" src="assets/Connecting to home network.png">
</div>

Then I ran few codes on printing Hello world in different ways, with different delays to understand on how to flash photon software, what happens during compilation, how to look at serial monitor, go deeper into delays and why they are important, below are my iterations.

Some playing videos:
1. Printing Hello world.
2. Printing Shryas Bhurat, but one word in a line.
3. Priting Shryas Bhurat, with different delay rates.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="33%" alt="Printing Hello World" src="assets/Adobe Express 2024-09-30 10.21.44.gif">
    <img width="33%" alt="Printing Shryas Bhurat but one word in a line" src="assets/Adobe Express 2024-09-30 10.19.10.gif">
    <img width="33%" alt="Priting Shryas Bhurat with different delay rates" src="assets/Adobe Express 2024-09-30 10.23.29.gif">
</div>


### Diagrammatic Analysis of a Microelectronics Project

Some playing videos:
1. Micro Electronics Circuit.
2. Micro Electronics Setup.
3. Micro Electronics Run.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="33%" alt="Micro Electronics Circuit" src="assets/microelectronics_intro.png">
    <img width="33%" alt="Micro Electronics Setup" src="assets/Adobe Express 2024-09-30 10.13.17.gif">
    <img width="33%" alt="Micro Electronics Run" src="assets/Adobe Express 2024-09-30 10.09.06.gif">
</div>

Then I put all that I learnt about resisters, photon, delays, flashing, connecting it to internet and bread boards to blink a bulb with 3 volts of voltage using the diagram shared on how to make connections, I also had to add few resistors so that the current flow can be reduced suitable for both bulb and the button added to change the delay randomization for the software.

The images/videos below show button pressed to change the speed of the delay (300 ms - 1000 ms & 30 ms to 300 ms), blinking fast and blinking slow based on button pressed to change the speed within the range.

Some playing videos:
1. Button Pressed shown on Terminal.
2. Blink Slow based on lower range on periodicity.
3. Blink Fast based on higher range on periodicity.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="33%" alt="Button Pressed shown on Terminal" src="assets/Adobe Express 2024-09-30 10.13.17.gif">
    <img width="33%" alt="Blink Slow based on lower range on periodicity" src="assets/Adobe Express 2024-09-30 10.09.06.gif">  
    <img width="33%" alt="Blink Fast based on higher range on periodicity" src="assets/Adobe Express 2024-09-30 10.06.09.gif">    
</div>

I also tried to use 2 LED's electronic wiring, with one more digital read out in use, connections similar to prebvious one but for a new LED.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="50%" alt="Button Pressed shown on Terminal" src="assets/2 bulb code.gif">
    <img width="50%" alt="Blink Slow based on lower range on periodicity" src="assets/2 bulbs.gif">    
</div>

Then went to on write a code that can make the LED's off when the button is pressed and once it is pressed again the LED's periodicity is randomized for 3 LED Setup.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="50%" alt="Button Pressed shown on Terminal" src="assets/3 buble code.gif">
    <img width="40%" alt="Blink Slow based on lower range on periodicity" src="assets/3 bulbs.gif">    
</div>

### Speculations

I think this will be a very useful skill and will help me to work on projects that have hardware aspects to it. I look forward to playing more with photon, to build a interactive tool that can take data realtime in a hardware setting and transfer it to the software aspects, so that we can learn from the tools/wearable that we use, similar to smart watches and digital devices.

### References:
- Link to changing wifi's: https://docs.particle.io/tools/developer-tools/configure-wi-fi/



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

#### Storyboard

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="52%" alt="Custom Keychain" src="assets/Storyboard.png">
</div>

- Frame 1: Moving to Berkeley, USA from Home back in India
- Frame 2: Moving to a new home without any furniture and essentials
- Frame 3: Its frustrating after long day at college to go back home and find the charger from the clunk of messy wires
- Frame 4: I use 3D Printing, parametric modeling using Grasshopper and design something that can help me solve this problem.
- Frame 5: Utilizing charging station concept where I can throw my watch to the stand, it sticks around and fuels my watch and phone.
- Frame 6: Easy to handle with edge fillets and understanding the model on how to use it.

### Project Challenge Level Rationale
#### Challenge level: 03 - Axolotl

I’m very new to grasshopper-based modeling and never used tools like these for modeling before. I had to figure out how to use it by watching videos and getting help from people around me in the cohort. I started working on Rhino first to see how the models are created in it, the user interface was quite daunting for me initially, but then playing around with the charger stand files shared, I started to interact with the system. I then tried to build a rectangular box on my own, just to see how the grasshopper modeling works, and then pursued to build something that I wanted for my home. I was new to 3D printing as well since I had to learn how support structures work, and tolerancing working on different systems and filaments to use. Working on these many iterations streamlined the process for me and I then built the model from scratch pushing myself to learn new things along the way, I learned a lot about dimensioning, modeling, tolerances, fillets, and other human-centered design aspects. Thus I consider this project to be an Axolotl level one.

### Working

My experiments with computational design technologies significantly influenced my Charging Station design. The parametric modeling capabilities of Grasshopper allowed me to easily adjust dimensions and features, facilitating rapid iterations and refinements. This flexibility, combined with my newly acquired knowledge of dimensioning, tolerances, and fillets, enabled me to create a more ergonomic and user-friendly design that incorporated important human factors considerations.

My exploration of 3D printing techniques directly impacted my design's printability. I adjusted my model to minimize support structures and optimize print time and material usage. The ability to quickly prototype and test designs allowed me to address challenges such as integrating the Apple Watch charger and refining the overall form factor. This iterative process, enabled by the combination of parametric modeling and 3D printing, ultimately led me to create a functional, customized charging station that effectively solved my initial problem while demonstrating the potential of computational design technologies in creating practical solutions.


<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="70%" alt="Custom Keychain" src="assets/Group 5.png">
</div>


#### To make it easy for me to utilize the resource while making it look elegant.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="32%" alt="Custom Keychain" src="assets/SCR-20240919-beds.png">
     <img width="32%" alt="Custom Keychain" src="assets/SCR-20240919-bdzg.png">
</div>

### Human Factors (AEIOU Framework)

- Activitiy: To solve the problem for a place/equipment where I can charge my mobile and iwatch without any issue, currently I keep it on the floor.
- Environments the activity takes place everyday when I get home from college and need to charge my watch and phone
- Interactions are between me and the charger that I use to charge the watch and phone, I charging seamlessness would depend on the time I keep them to charge and usually its frustrating to find the right charger, turn and unturn them because they get messy overtime.
- Objects I utilized sketches, design on grasshopper, dimensioning and tolerancing, 3d printing software, perplexity to solve my queries to build it.
- User: I’m the user and I’m usually tired going home after college and want to instantly put all my electronics gadgets on charge, the immediate need to find the charger that fits well on the first time was really crucial for me as I went on to solve this problem. It has to have human factors included in the design so that it can be handled easily.


#### Youtube Video
https://www.youtube.com/watch?v=eQastMoem7A (fun video to watch)

After trying out 3D printing, I decided to learn something new - video editing. I made a video that shows all the different things I've been working on lately. This video is like a big picture of my projects. It probably shows my 3D printed stuff, but it also has parts where I used my new video editing skills. I might have added cool transitions between scenes, made the colors look better, fixed the sound, or even put in some special effects. By making this video, I got to practice my new editing skills while also showing off my 3D printing work. 

### Images

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="32%" alt="Custom Keychain" src="assets/WhatsApp Image 2024-09-18 at 21.47.49 (1).jpeg">
    <img width="32%" alt="Custom Keychain" src="assets/WhatsApp Image 2024-09-18 at 21.47.49.jpeg">
</div>

### Outcomes
- The working battery charging stand prototype, so that it can charge my phone easily.
- Human factors into consideration with fillets and wire extrusions so that it look neat, tidy and sturdy.
- Form factor so that it can seamlessly integrate with in my surroundings in the room.

### Speculations

I thought everything would work perfectly on my first try with 3D printing, but I was wrong. I had to do it over and over again, learning more each time. This taught me a lot about how 3D printers work and what they can and can't do well. I found out that tiny differences in measurements matter a lot in 3D printing. By trying many times and making small changes, I got better at understanding how the printer, the materials, and my designs all work together. Now, I can make better 3D prints, and I really see how amazing and tricky 3D printing can be for making things.

#### Exploring computational design technologies

As a newcomer to computational design, I immersed myself in learning Grasshopper and Rhino. I started by familiarizing myself with Rhino's interface, which I initially found daunting. To gain comfort, I examined existing charger stand files and practiced creating basic shapes & playing around with pre built model. This foundation allowed me to transition into Grasshopper, where I began experimenting with parametric modeling by creating simple geometries like rectangular boxes. I relied heavily on tutorial videos and sought assistance from my cohort members. This iterative learning process enabled me to progress from basic shapes to more complex designs in Grasshopper. Simultaneously, I explored 3D printing technology, experimenting with support structures, various filaments, and printer settings. This hands-on approach to both digital modeling and physical production gave me a comprehensive understanding of the entire design-to-fabrication process, which was crucial for my project's success.

### Conclusion: 
My Charging Station project has been a great journey into the world of computational design and digital fabrication. As a novice in Grasshopper-based modeling and 3D printing, I faced numerous challenges that pushed me to develop new skills and problem-solving abilities. Through iterative design and prototyping, I not only created a functional solution to my everyday charging needs but also gained valuable insights into parametric modeling, human-centered design, and additive manufacturing. This experience has demonstrated the power of computational design tools in solving real-world problems and how they can empower individuals to create customized solutions. The project's success, evidenced by a functional and aesthetically pleasing charging station that integrates seamlessly into my living space, stands as a testament to the potential of combining creativity with technology, has also laid a strong foundation for future endeavors in design and engineering, showcasing the immense value of learning through hands-on experience and perseverance.



---------------------------------------------------------------------------------------------------------

# Week 2: Exploring Rhino Grasshopper and 3D Printing this week #
## Week of 09/07/2024

### Reflections
Rhino seems like an interesting software to build things as it is parametric and things can be edited quite quickly because of this. I wanted to make the phone stand for my phone dimensions so that I could keep it comfortably on my study table.

#### Diagrams

My Understanding of Parametric Modeling

I've found out that Rhino is a really cool software for making things. It's special because it lets me change my designs quickly and easily. This is because it uses something called parametric modeling. I want to use Rhino to make a phone stand that fits my phone perfectly and looks good on my study table. I'm excited to put in my phone's size and play around with different designs. I can change things like how tall the stand is, what angle it sits at, and even add a spot for my charging cable. The best part is, if I want to change anything, I just need to change some numbers and the whole design updates by itself.

This way of designing things is great because I can try out lots of different ideas really fast. I don't have to start over from the beginning every time I want to make a small change. I'm looking forward to making something that's not just useful, but exactly right for me and my study setup. Plus, I'll be learning how to use a powerful tool that I can use for other projects in the future. Once I'm happy with my design, I might even 3D print it or find another way to make my custom phone stand for real. I think this project will help me understand how to make things that can easily change and grow with what I need.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="50%" alt="Custom Keychain" src="assets/Rhino Modelling.png">
</div>


I tried to edit the parameters to the iPhone XR dimensions
<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="32%" alt="Custom Keychain" src="assets/Param1.png">
    <img width="32%" alt="Custom Keychain" src="assets/Param.png">
</div>

When I first tried to make my phone stand, I ran into a problem. The base I designed wasn't thick enough, which meant the center of gravity (CG) of my phone was outside the area that would keep it stable. This is because the CG is really important for keeping things from tipping over. If the CG is too far outside the base, the object will fall.

To fix this, I had to think creatively. I decided to change the angle of how the phone sits on the stand. By adjusting the angle, I was able to bring the CG back inside the stable area. This made the whole stand much more stable, even with a thinner base. It was a good lesson for me in how small changes in design can make a big difference in how well something works. I learned that when designing things like phone stands, it's not just about how it looks, but also about understanding basic physics principles like center of gravity and stability.

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="32%" alt="Custom Keychain" src="assets/Sizedifference.png">
    <img width="32%" alt="Custom Keychain" src="assets/Assemnotgood.png">
</div>

It worked, the phone was more stable and I could bake the results instantly & then I tried to replace the base with a cylinder.

#### Images

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="32%" alt="Custom Keychain" src="assets/Assemgood.png">
    <img width="32%" alt="Custom Keychain" src="assets/phonestand3dprinted.png">
     <img width="32%" alt="Custom Keychain" src="assets/Cylinderinsteadofsphere.png">
</div>

I then created a 3D file to print the output so that I could use it.

#### Box for storage near my bed

I attempted to create a custom design using Grasshopper, a visual programming tool for 3D modeling. My goal was to make a practical storage solution for the area near my bed. Specifically, I wanted to design a box that could neatly organize and hold my various chargers. This project aimed to combine functionality with personalized design, allowing me to keep my bedside area tidy and have easy access to my charging cables. By using Grasshopper, I could experiment with different shapes, sizes, and compartments to create a box that perfectly fit my needs and the available space next to my bed.

#### Images

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
    <img width="32%" alt="Custom Keychain" src="assets/TableOnRhino.png">
    <img width="32%" alt="Custom Keychain" src="assets/3DPrintingtable.png">
     <img width="32%" alt="Custom Keychain" src="assets/BoxforBed.jpeg">
</div>

#### Speculations

It was fun to play with parameters and very quick iterations. I see this being used with the technology and large learning models to build cad models faster. I also see me using this tool to enable me for fast prototyping and learn from failures faster.

I've discovered that Rhino is a really cool software for building things, especially because it's parametric, which means I can edit my designs quickly and easily. I've decided to use it to make a phone stand that's perfect for my phone's dimensions. This way, I can keep my phone comfortably on my study table while I work. I was excited to input my phone's measurements and play around with different designs. I can adjust things like the angle of the stand, how tall it is, and even add a spot for my charging cable. What's great is that if I want to change anything, I can just tweak the numbers and the whole design will update automatically. This means I can experiment with different ideas until I get the stand just right for my study setup. 

I'm looking forward to creating something that's not only useful but also perfectly tailored to my needs.



---------------------------------------------------------------------------------------------------------

# Week 1: Personalizing My New Berkeley Home #
## Week of 09/05/2024

### Reflections

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

