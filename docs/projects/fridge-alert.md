# Fridge Alert

## Introduction @unplugged

Write code to alert a scientist that the fridge door has been left open using the light sensor, so they know to immediately close the door!


## Step 1 @fullscreen


Place a ``||basic: show number||`` block in the ``||basic:forever||`` block.



## Step 2

Place a `||input: light level||` block in the ``||basic: show number||`` block.
Test your code on the simulator using the half moon icon on the top left to change the light level.
Remember this number as it will help us later!


## Step 3

Find the `||logic: 0 > 0 ||` comparison block that will help us compare `||input: light level||` with a number. 


## Step 4

Use an `||logic: if true then ||` block to play a `||music: melody ||` when the  `||input: light level ||` is greater than your ambient reading.
You can remove the ``||basic: show number||`` block if you like

## Step 5

Find the  `||input: on button A pressed ||` block and ``||basic: show icon X ||`` when this button is pressed

## Step 5

Finally, stop the `||music: stop melody background||` when the button is pressed.

This would allow a scientist to confirm they have checked the contents of the fridge.

## Step 4

If you have a @boardname@ connected, click ``|Download|`` to transfer your code and test your Fridge Alert!
