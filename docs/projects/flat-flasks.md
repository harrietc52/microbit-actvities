### @explicitHints true

# Flat Flask

## Introduction @unplugged

**Write code to alert a scientist if the flask is not completed flat, as this will drain liquid off the cells and kill them.**

Scientists use multilayer flasks to grow cells as there is more surface layer than an ordinary single layer flask. However, because each layer in the flask contains liquid to feed the cells, it is important that the flask remains completely flat. Otherwise, the liquid will drain out of the corner and the cells will dry out.  

## Step 1 @fullscreen


Remove the ``||basic: on start ||`` block from the editor by drag and drop onto the coding block pane

### ~ tutorialhint There will be hints available to help guide you through the steps



## Step 2 


Place a ``||basic: show leds ||`` block in the ``||basic:forever||`` block to show a smiley face.

### ~ tutorialhint You can click on the LED grid, and drag you mouse to create a picture. As this is in the forever block, it will always show your picture. Test this in the simulator

## Step 3

Add an `||logic: if true then ||` block to only show the smiley face when `||logic: true ||`

Remember to test in the simulator by changing  `||logic: true ||` to  `||logic: false ||`

### ~ tutorialhint You need to put the show LEDS block, inside the if true block. When it is set to true, the picture should be displayed. When it is false, the picture will not be displayed.


## Step 4

Replace `||logic: true ||` with `||input: is screen up gesture ||`

### ~ tutorialhint You may find this block within the `||input: is shake gesture ||`



## Step 5

Extend the `||logic: if true then ||` block to include `||logic: else ||` and 
place the ``||basic: clear screen ||`` block into the space

### ~ tutorialhint To add else, click the `||logic: + ||` button. Try testing this by moving your mouse over the simulator to tilt the micro bit and make sure the screen is cleared

 
## Step 6

Look at what other gestures the `||input: is screen up gesture ||` block can sense. 
Is there one for on  `||input: tilt ||`?


## Step 7

Display the letter `R` on `||input: tilt right ||` and `L` `||input: tilt left ||` 
You may need to click the ``||logic: + ||`` button to extend the ``||logic: if / else ||`` block




## Step 8

**Advanced**: Instead of dispaying letters, use ``||music: music ||`` to alert when the Micro:bit is tilted

Remeber to add code so the Micro:bit does not make any sound when it is flat

### ~ tutorialhint You can use any output to alert that it is not flat. Try discovering other ways



## Step 9

**Advanced**: Hold up the micro:bit and tilt it from side to side. This time try and display the x/y/z degree using the `|| input: acceleration ||` block

### ~ tutorialhint Read here about the micro:bits acceleration input. https://makecode.microbit.org/reference/input/acceleration 




## Step 10

**Advanced**: 

Use the `|| input: acceleration ||` block to play a different tone of noise, depending on how much the micro:bit is tilted. 

Remembering to not play any noise when the micro:bit is flat - as the cells are safe!

### ~ tutorialhint To achieve a sound on both the `|| input: x ||` and `|| input: y ||` axis, you will need to use `|| math: acceleration + 1024 ||` to increase the range. 


## Step 11

If you have a Micro:bit connected, click ``|Download|`` to transfer your code and test your Flat Flask!
