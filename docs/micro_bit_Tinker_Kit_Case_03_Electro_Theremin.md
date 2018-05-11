micro_bit_Tinker_Kit_Case_03_Electro_Theremin.md

![](https://i.imgur.com/TJvoaaV.jpg)  

## Goals  
---
Learn to use an analog sensor with the micro:bit.  
Make an electro-theremin!  


## Materials  
---
1 x [BBC micro:bit](http://www.elecfreaks.com/estore/micro-bit-board.html)  
1 x Micro USB cable  
1 x [Buzzer](https://www.elecfreaks.com/estore/octopus-passive-buzzer-brick-obpb01.html)  
2 x F-F Jumper Wires  
1 x Potentiometer  
 
## Procedure      
---
### Step 1  
Plug in your Buzzer to Pin0. Make sure the positive lead is connected to the yellow signal pin and the negative lead is connected to the black ground pin on the breakout board.  
Plug in the potentiometer to Pin1. You can plug according to the color. Make sure that the wire colors and the pin colors on breakout board are well matched!  

![](https://i.imgur.com/PUPIRol.jpg)  

### Step 2  
In Makecode, we’ll track the value of the potentiometer using a variable. Variables are like buckets that can hold changing values.
Make a new variable called reading (or anything you like, really) in the Variable drawer.  
We want to constantly set our reading variable to the analog value of the potentiometer instead of the digital.  
Reading the analog value allows us to access a whole range of signals from the potentiometer, instead of just a digital 1 or 0. Find this block in the Pins drawer.  

![](https://i.imgur.com/DMXaJD9.png)  

### Step 3  
Check your minimum and maximum values for your potentiometer by showing the number of the reading variable.  
Turning the knob anti-clockwise all the way gives you the minimum, and clockwise all the way gives you maximum.  
Notice how the values jump? That’s because the micro:bit takes some time to scroll a large number across the screen, and by the time you read a new value, the potentiometer would be way ahead!   

![](https://i.imgur.com/eNZiQx8.png)  

### Step 4  
Now we’re going to use those values you just read from your potentiometer to map out your notes!  
Our music blocks may not have a range as wide as your potentiometer. In this instance, we want to make sure the highest potentiometer value still corresponds to the highest note we can play.  
Check out the value of the lowest and highest notes in the micro:bit piano keys.   
Using the map block from the Pins drawer to key in all the values.   

![](https://i.imgur.com/WF67giW.png)  

### Step 5  
You may have noticed we made another variable called note in the previous step. Make sure you set the note variable to the mapped values. Ring the tone using the note variable. Upload it all into your micro:bit and you are ready to make some noise!  

![](https://i.imgur.com/laFfa5r.jpg)  

### Cool stuff!  
Now you’ve learned how to play around with the potentiometer, you can try to use it to control LEDs, servos, and other components! And if you get your hands on another analog sensor, you’ll know just how to use it!  
