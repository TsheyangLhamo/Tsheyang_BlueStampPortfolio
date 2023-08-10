# Lie Detector 
Were you ever in a situation where you wanted to know if your friend was lying to you? Well in this project, we can determine just that by measuring the change in someone's skin conductivity depending on their mood. 

```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Tsheyang L | Fiorello H. Laguardia High shcool | Computer Science | Incoming Senior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my final milestone, I soldered the Led lights and added a 10 k potentiometer to change the sensitivity. Then I added a lid, with a hole so the led lights can poke out. Something I struggled with was trying to solder my Led lights, because the wires would randomly fall off and my iron wouldn't let me melt the solder properly, but after a lot of tries I ended up getting that done. Overall at bluestamp, I learned the basics of breadboarding and how to solder. In the future, I hope to create more projects and gain more soldering practice.


# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/PkrtjiQfmDU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my second milestone, I stripped the two wires and used aluminum foil and velcro to make the finger straps, and I made a box for my arduino and breadboard out of cardboard. I added two holes for the finger straps to go through and for the wire to be able to connect to my computer. For now, we can determine if someone was lying based on the serial plotter. It indirectly measures the person's skin conductivity shown on a graph by outputting a voltage dependent on the skin conductivity which will help identify when the data changes its pattern. If the pattern changes, then it means the person was lying. A struggle I am currently facing is trying to get my Led lights to turn on. Which is what I am going to fix for milestone 3. I am gonna try changing the size of my resistor to change the sensitivity (adding a potentiometer will let the user vary the resistance in real time) and I am also adding a battery pack so I don’t have to keep my lie detector connected to my computer. 


# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/t69B1PQtK7U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

My first milestone was to wire up my breadboard to have the three LED lights turn on when the red and white wires touch each other. I connected my Arduino UNO to my breadboard and downloaded my code for it. I also added a 2K resistor to divide the current. I struggled at first trying to learn the basics of breadboarding, so I watched many videos. The resistor would also not stay in place, which made it difficult to work all together. But after many adjustments, I got it to work! For the next Milestone I am going to create the finger straps for the two wires and build it a home using cardboard.


# Schematics 
![Headstone Image](Screenshot-2023-07-26-at-10.26.47-AM.PNG)
![Headstone Image](IMG-9776.JPG)

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
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
