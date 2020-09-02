### @explicitHints true

# Fridge Alert

## Introduction @unplugged

**Write code to alert a scientist that the fridge door has been left open using the light sensor, so they know to immediately close the door!**

Hazardous chemicals or precious samples are kept in fridges, so that only trained scientists have access to them and everyone is kept safe and the samples are kept alive. Therefore doors on these cabinets cannot be left open for a long period of time. 


## Step 1 @fullscreen


Remove the ``||basic: on start ||`` block from the editor by drag and drop onto the coding block pane

### ~ tutorialhint There will be hints available to help guide you through the steps


## Step 2


Place a ``||basic: show number||`` block in the ``||basic:forever||`` block.

### ~ tutorialhint Check the simulator that `0` is displayed


## Step 3

Place a `||input: light level||` block where the ``||basic: show number||`` block says `0`.

Use the half moon icon on the simulator to change the level of the light. Remember the `||input: light level||` number as it will help us later!

### ~ tutorialhint Click and drag half moon on the top left of the simulator to change the light level. 


## Step 4

Find the `||logic: 0 = 0 ||` comparison block and change `||logic: 0 = 0 ||` to `||logic: 0 > 0 ||`

## Step 5

Use an `||logic: if true then ||` block to show the `||input: light level||` number when `||input: light level||` `||logic: > ||` `remembered number`

### ~ tutorialhint Right click > duplicate on a block to copy and paste the block


## Step 6

Instead of displaying the  `||input: light level||`, play a `||music: melody ||` with a fast `||music: tempo ||`

You can remove the ``||basic: show number||`` block now we know our light level reading

### ~ tutorialhint Remember to create a melody by clicking next to the music icon in the `||music: play melody .. at tempo ||` block

## Step 7

Find the  `||input: on button A pressed ||` block and ``||basic: show icon ||`` when this button is pressed



## Step 8

Finally, stop the `||music: stop melody background||` when the button is pressed.

This would allow a scientist to confirm they have checked the contents of the fridge.

### ~ tutorialhint Multiple blocks can be sandwitched between `||input: on button A pressed ||`. Drag and drop above or below other  blocks


## Step 9

If you have a @boardname@ connected, click ``|Download|`` to transfer your code and test your Fridge Alert!
