# Assignment1-FirstWebsite

## LEARNING HOW TO ROLLER SKATE
### INTRODUCTION

I went rollerskating this weekend, so thought I would make a rollerskating-inspired website. I haven’t been rollerskating in over 15 years, so I found myself going over the basics steps in my head. I thought I would translate those steps into a fun website showcasing (and oversimplifying) how to rollerskate and created a rollerskate image.

### PROCESS
**Design**

I was inspired by the layout of this CSS example of step by step tutorial guide. 
![alt text](https://raw.githubusercontent.com/itp-dwd/2020-spring/master/assets/css__selectors-01.png)


I created a similar layout and experimented with the text types, padding and margins. I made each separate step (Step 1, Step2, Step 3) using a container that stated the numbered step and the step itself. 

**Setting Up My Environment**

Since, CSS and HTML are new languages to me, I was watching a few CSS and HTML tutorials and found one vital tip that helped me set up my environment. In VSCode, instead of using inline CSS, I created two separate files: CSS and HTMl files. That way I could distinguish between the skeleton, or the HTML, and the design of the site separately. To link my CSS file to my HTML file I used link rel="stylesheet" type="text/css" href="Style.css">, where my CSS file was labeled "Style.css". I originally 
created a new folder to house my CSS file, but had issues uploading the folder to Github(more on this later). 

**Creating My Website**

I wanted to use shapes to create a roller skate on the site. Since I would create multiple shapes (rectangles for the leg and shoe, circles for the wheels) to create one cohesive roller skate, I wanted to form some type of relationship between these shapes. The foot, a rectangle, would be the base which all the other shapes would adapt around. I found that I could use 'position: relative' to place the shoe relative to its current position without changing the layout around it and 'position: absolute' to place the leg and wheels relative to the parent position (in this case the foot).

I was also inspired by the artist RAFAËL ROZENDAAL on Rhizome, with his usage of shapes and shades of color that looked like the covers were overlapping. 

![alt text](https://artbase.rhizome.org/images/f/f4/Ca-2947.jpg)

So, I decided to create an overlapping color illusion between the roller skate and the wheels, by overlaying the dark navy blue wheels with the white shoe to create a light blue overall. Originally, I wanted the overlapping light blue to align exactly between the shoe and wheels, but I was hardcording the exact location and size of the overlapping section so it wasn't precise and visually looked off. So, I adapted to create a small section that's overlapping. 

### DEPLOYMENT

Initially, I had a few problems with deployment. The path way of my index.html files was Desktop>DynamicWeb>Assignment1>index.html. In my Assignment1 folder, I created a CSS folder to house my Style.CSS file. Originally, I deployed my entire Assignment1 folder to Github and tried to push to Glitch. However, there was an error and my website would not load. I think it's because I can't upload a folder with a folder in it? I went back and deleted my CSS folder and put my Style.CSS and index.html files into my  Assignment1 folder. Then, I thought I lost my index.html as I transfered my index.html file momentarily out of my Assignment1 folder and had to use Terminal a few times to determine the exact location of my files. Overall, 1) why could I not upload my Assignment1 folder with my CSS folder and 2) how can I know what files to move around in my folders without the fear of losing something because it's in a different location on my computer?

### GENERAL QUESTIONS

1. I spent a long time trying to move my shapes to the center of the canvas. I originally hardcoded a shape coordinate in VSCode through estimation and constantly refreshed my website as I was updating my coordinates. I had a classmate give me a tip to use "Inspect" in the browser, where I could change the properties of CSS classes manually and see changes live. When I could see the coordinates I wanted, I could write those coordinates into my VSCode. This saved  me time in my workflow. However, is there a way to get shapes to be a certain percentage of the canvas(1/2, 1/3, etc.) without hardcoding numbers?
2. In p5.js, we used a class to create a unique shape that we would want to replicate again. In this assignment, I created a parent-child relationship between my shapes to create one roller skate. However, I couldn't call the "class" of a roller skate without copying and pasting all the parts of the roller skate class. Is there a way to create a general "class" in HTML/CSS?



