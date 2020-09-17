### @explicitHints true

# Flat Flask

## Introduction @unplugged

**Write code to alert a scientist if the flask is not completed flat, as this will drain liquid off the cells and kill them.**

Scientists use multilayer flasks to grow cells as there is more surface layer than an ordinary single layer flask. However, because each layer in the flask contains liquid to feed the cells, it is important that the flask remains completely flat. Otherwise, the liquid will drain out of the corner and the cells will dry out.  

## Step 1 @fullscreen


Remove the ``||basic: on start ||`` block from the editor by drag and drop onto the coding block pane

### ~ tutorialhint There will be hints available to help guide you through the steps



## Step 2 


Place a ``||basic: show leds ||`` block in the ``||basic:forever||`` block to show a picture of your making!

### ~ tutorialhint You can click on the LED grid, and drag you mouse to create a picture. As this is in the forever block, it will always show your picture. 

Remember to test in the simulator!

## Step 3

Add an `||logic: if true then ||` block to only show your picture when `||logic: true ||`

### ~ tutorialhint You need to put the show LEDS block, inside the if true block. When it is set to `||logic: true ||`, the picture should be displayed. When it is `||logic: false ||`, the picture will not be displayed.


## Step 4

Replace `||logic: true ||` with `||input: is screen up gesture ||`

### ~ tutorialhint You may find this block within the `||input: is shake gesture ||`



## Step 5

Extend the ``||logic: if true then ||`` block to include ``||logic: else ||`` and 
place the ``||basic: clear screen ||`` block into the space. 


### ~ tutorialhint To add ``||logic: else ||``, click the ``||logic: + ||`` button. 

Try testing this by moving your mouse over the simulator to tilt the micro bit and make sure the screen is cleared

 
## Step 6

Look at what other gestures the `||input: is screen up gesture ||` block can sense. 
Is there one for on  `||input: tilt ||`?


## Step 7

Display the letter `R` on `||input: tilt right ||` and `L` `||input: tilt left ||` 
You may need to click the ``||logic: + ||`` button to extend the ``||logic: if / else if ||`` block

### ~ tutorialhint Remember to `||input: clear screen ||` in the ``||logic: else ||`` block



## Step 8

Instead of dispaying letters, use ``||music: play melody ||`` to play a high note when the micro:bit is tilted right, and a low note when the micro:bit is tilted left.

Remember to add code so the Micro:bit does not make any sound when it is flat using ``||music: stop melody backgound ||``

### ~ tutorialhint You can use any of the other ``||music: music ||`` blocks. Try discovering other ways!  

When using ``||music: ring tone ||`` you will need to ``||music: set volume ||`` to hear the music and ``||music: set volume 0 ||`` to stop the music.

## Step 9

**CONGRATULATIONS** you have successfully alerted the scientists that their samples are safe when the micro:bit is flat!

Continue with the next steps if you would like to discover an alternative solution using more advanced blocks.


## Step 10

**Advanced** 

Remove all your code apart from the `||basic: forever ||` block

Hold up the micro:bit and tilt it from side to side. Use  `||basic: show number ||` to display the x/y/z degree using the `|| input: acceleration (mg) x ||` block 

### ~ tutorialhint `x` is acceleration in the left and right direction. This ranges from -1023 to 1023

Read here about the micro:bits acceleration input. https://makecode.microbit.org/reference/input/acceleration 



## Step 10

**Advanced** 

Use the ``||music: ring tone ||`` block to play a constant stream of noise. 

Replace ``||music: Middle C ||`` with `|| input: acceleration (mg) x ||` as this number will change the tone as we tilt the micro:bit. 

Try tilting the micro:bit and listen to the diffent tones ... is there anything unexpected?!


## Step 11

**Advanced**

YES! The micro:bit is only making a noise when you tilt it to the right!

This is because our ``||music: ring tone ||`` input only understands possitive numbers and when we tilt the micro:bit left, ``|| input: acceleration (mg) x ||`` is a negative number. 

To fix this, find the Math block ``||math: 0 + 0 ||`` and change it to `|| input: acceleration (mg) x ||` ``||math: + 1023 ||``, as we know the range of the `x` axis is `1023`. 


## Step 12

**Advanced**

However, the micro:bit is still playing a noise when the micro:bit is flat and the samples safe! 

How might you be able to stop the noise when the micro:bit is flat using ``|| input: acceleration (mg) x||``?

### ~ tutorialhint Inside an ``||logic: if ||`` block you can check when ``|| input: acceleration ||`` ``||logic: = 0 ||``

Inside this block make no noise using ``||music: rest 1 beat ||``



## Step 11

**CONGRATULATIONS** you have successfully alerted the scientists that their samples are safe!

If you have a Micro:bit connected, click ``|Download|`` to transfer your code and test your Flat Flask!
