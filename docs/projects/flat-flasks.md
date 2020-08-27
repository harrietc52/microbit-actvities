# Flat Flask

## Introduction @unplugged

Write code to alert a scientist if the flask is not completed flat, as this will drain liquid off the cells and kill them.


## Step 1 @fullscreen


Place a ``||basic: show leds ||`` block in the ``||basic:forever||`` block to always show a smiley face.



## Step 2

Add an `||logic: if true then ||` block to only show the smiley face when `||logic: true ||`

Test this to make sure by changing  `||logic: true ||` to  `||logic: false ||`



## Step 3

Replace `||logic: true ||` with `||input: is screen up gesture ||`



## Step 4

Extend the `||logic: if true then ||` block to include `||logic: else ||` and 
place the ``||basic: clear screen ||`` block into the space

 
## Step 5

Look at what other gestures the `||input: is screen up gesture ||` block can sense. 
Is there one for on tilt?


## Step 5

Use LEDS to display letters on `||input: tilt right ||` and  `||input: tilt left ||` 
You may need to click the ``||logic: + ||`` button to extend the ``||logic: if / else ||`` block


## Step 6

Instead of dispaying letters, use ``||music: music ||`` to alert when the Micro:bit is tilted

Remeber to add code so the Micro:bit does not make any sounds when it is flat


## Step 7

If you have a Micro:bit connected, click ``|Download|`` to transfer your code and test your Flat Flask!
