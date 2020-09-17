### @explicitHints true

# Fridge Alert

## Introduction @unplugged

**Imagine the micro:bit is kept inside a fridge. Write code to alert a scientist that the fridge door has been left open using the light sensor, so they know to immediately close the door!**

Hazardous chemicals or precious samples are kept in fridges, so that only trained scientists have access to them and everyone is kept safe and the samples are kept alive. Therefore doors on these cabinets cannot be left open for a long period of time. 


## Step 1 @fullscreen


Drag and drop the ``||basic: on start ||`` block onto the coding block pane to remove it from the editor.

### ~ tutorialhint There will be hints available to help guide you through the steps


## Step 2


Place a ``||basic: show number||`` block in the ``||basic:forever||`` block.

### ~ tutorialhint Remember to check the simulator that `0` is displayed or click ``|Download|`` to test on your micro:bit 


## Step 3

Place a `||input: light level||` block where the ``||basic: show number||`` block says `0` and note down the number displayed on the micro:bit as we will need this later!

### ~ tutorialhint Click and drag the half moon icon at the top left of the simulator to change the `||input: light level||`. 

If using a micro:bit, click ``|Download|`` and see what the light level in your room is!

## Step 4

Create a `||variable: variable||` called `||variable: mylightlevel||`

Use the block `||variable: set mylightlevel to 0 ||` and change `0` to your noted light level.

Drag the block above ``||basic: show number||``


### ~ tutorialhint To make a variable: Click `||variable: Make a Variable||`. 



## Step 5

Find the `||logic: logic ||` comparison block that would allow us to compare if a number is greater than another number.

This is useful because when the fridge door is left open the light will be greater than when the fridge door is left shut!

### ~ tutorialhint You could use the  `||logic: 0 = 0 ||` comparison block and change `||logic: 0 = 0 ||` to `||logic: 0 > 0 ||`.


## Step 6

Use an `||logic: if true then ||` block to ``||basic: show number||`` when `||input: light level||` `||logic: > ||` `||variable: mylightlevel ||`

### ~ tutorialhint Only wrap the `||logic: if true then ||` block around the ``||basic: show number||`` block, **not** the `||variable: set ||` block

Remember to test on the simulator!

## Step 7

Instead of displaying the  `||input: light level||`, play a `||music: melody ||` with a fast `||music: tempo ||`

You can remove the ``||basic: show number||`` block now we know our light level reading


### ~ tutorialhint Remember to create a melody by clicking next to the music icon in the `||music: play melody .. at tempo ||` block

## Step 8

**CONGRATULATIONS** you have alerted a Scientist that their fridge door has opened!

**Optional:** Find the  `||input: on button A pressed ||` block and ``||basic: show icon ||`` when this button is pressed


## Step 9

**Optional:** Stop the `||music: stop melody background||` when the button is pressed.

This would allow a scientist to confirm they have checked the contents of the fridge

### ~ tutorialhint Multiple blocks can be sandwitched between `||input: on button A pressed ||`. Drag and drop above or below other  blocks


## Step 10

If you have a @boardname@ connected, click ``|Download|`` to transfer your code and test your Fridge Alert!

Try other blocks and discover more ways you could alert a Scientist that their fridge door has been opened!