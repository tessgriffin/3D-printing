# Beginning 3D Printing on the Lulzbot Taz 4

## Downloading Cura for Lulzbot Taz 4

The first step to using our Lulzbot here at Turing is to download the application. The link is [here](https://www.lulzbot.com/learn/tutorials/cura-lulzbot-edition-installation-osx)
There are instructions on the website on how to download the program.

When you open up the program for the first time, you'll need to indicate which printer you're using. We are using the Lulzbot Taz 4

## What are you printing?

What exactly are you printing? For us first timers, let's find a cool print online.

Example places to find 3D printable models:

  * [Thingiverse](http://www.thingiverse.com/)
  * [Pinshape](https://pinshape.com/)
  * [My Mini Factory](https://www.myminifactory.com)
  * [Yeggi](http://www.yeggi.com/)

For our example, we'll be printing out [Pikachu!](http://www.thingiverse.com/thing:22012)

## Using Cura software

When we downloaded Pikachu, it downloaded a .zip folder. When we unzip it, we can see 2 `.stl` files. For the purposes of the 3D printer, we want `.stl` files. There are many other types of 3D model files, including `.obj`.

Open up the Cura app, and look at the toolbar on the left hand side. There are plenty of settings depending on your experience level.

  * Material Ease of use to beginner
  * Material is PLA(eSun)
  * Standard Profile
  * Select Print Brim

When we print a brim, it prints out an extra bottom layer that helps the plastic stick to the bottom. Optionally you can print a support structure for unstable models.

### Loading the Model

Next we'll load our model.
![alt text](http://g.recordit.co/PI1GIKCcUS.gif "Load Model")

This is a visual representation of the actual ground and how big the printed model will be. To change how big pikachu will print, hit the scale. 

![alt text](http://g.recordit.co/ZhR9b26wBG.gif "Scale Model")

As you can see, Pikachu is only 32 mm or about 1.25 inches. That's tiny! Let's change the scale to 2. You can see when you update the scale, the time estimate on the upper left changes. It's just an estimate though. Pikachu at this scale will take almost 2 hours to print!

### Exporting the Model

Now, we have to export the model. Insert an SD card into your computer. Hit `save gcode`. Save it on the SD card, and it will save a `.gcode` file on the card.

## Operating the Printer

### Important Notes on the Printer

  * We've switched to using only PLA plastic because it doesn't crack in between layers.
  * PLA, if left **unmoving** in a heated nozzle will crystalize and clog up the nozzle. If this happens, Turing has to replace the nozzle at the cost of **150$**
  * To prevent this, as soon as the nozzle is heated up start printing.
  * Never leave the running printer unattended for more than 30 minutes. If the PLA happens to break, the printer can't tell and will continue to print, causing it to crystalize!
  * **Never set nozzle temp above 230!**

### Actual Operation

  1. Under the Control menu, set the nozzle temperature to 190 and the bed temperature to 65
  2. Once the nozzle reaches full temperature, select "Print From SD" and navigate to your file.
  3. The printer will automatically cool down when done printing, so you don't need to turn it off yourself
  4. Make sure to monitor the first few minutes to make sure the beginning sticks to the bed. Go by the printer about every 30 minutes to make sure it's printing OK.

### Changing Filament Colors
  
  1. Plug in your computer to the machine. Open up Cura and a new menu will pop up
  2. Raise the z-axis to 50mm
  3. Set the nozzle temp to 190. Once it's reached full temp take out the old one and put the new one in. Extrude the filament until you see the filament change colors.
