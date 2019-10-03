# Paper Puppets

*A lab report by Fabio Daiber*

## In this Report

To submit your lab, clone [this repository](https://github.com/FAR-Lab/IDD-Fa18-Lab4). You'll need to describe your design, include a video of your paper display in operation, and upload any code you wrote to make it move.

## Part A. Actuating DC motors

[Vibration Video](https://drive.google.com/open?id=1isKOBMmfbaOxNuLnahqa5YrcVpXh_io0)

## Part B. Actuating Servo motors

### Part 1. Connect the Servo to your breadboard

**a. Which color wires correspond to power, ground and signal?**

Red corresponds to power, orange to signal and brown to ground.

### Part 2. Connect the Servo to your Arduino

**a. Which Arduino pin should the signal line of the servo be attached to?**

We have to connect it to pin 9 or change ```myservo.attach(9);```

**b. What aspects of the Servo code control angle or speed?**

The angle is controlled by this part of the code ```pos = 0; pos <= 180; pos += 1```and to corresponding part ```pos = 180; pos >= 0; pos -= 1```.
There is two ways to change the speed. We can simply change the  ```delay(1); ``` function or we can change the position increments: ```pos += 1```


## Part C. Integrating input and output

**Include a photo/movie of your raw circuit in action.**

![alt text](https://github.com/fpdaiber/IDD-Fa19-Lab4/blob/master/IMG_2503.jpg)

I changed the delay function to read-in value of the potentiometer on pin 0, so I can control the speed of the servo.

Here's a video of it:
[Servo Video](https://drive.google.com/open?id=1Tl09XW48sgCKS4SdLj2nl0IF0YdvIIM7)

## Part D. Paper puppet

**a. Make a video of your proto puppet.**


[Puppet Code](https://github.com/fpdaiber/IDD-Fa19-Lab4/blob/master/Sweep_custom.ino)

A picture of my Paper Puppet: 
![alt text](https://github.com/fpdaiber/IDD-Fa19-Lab4/blob/master/IMG_2506.jpg)

[Paper Puppet in Action](https://drive.google.com/open?id=1mFsz0HgUdKCluEyXN6JpKxVwe3Brqm07)



## Part E. Make it your own

**a. Make a video of your final design.**

I laser cut a picture of myself and used by beer bottle from Lab 5 to create a Oktoberfest version of my puppet. I changed the arms of the puppet so that that my puppet is holding them up (and cheering). I also had to adapt the values of the code, so the arms move up. 
[My custom code ](https://github.com/fpdaiber/IDD-Fa19-Lab4/blob/master/Sweep_puppet_custom.ino)

A picture of my final design: 
![alt text](https://github.com/fpdaiber/IDD-Fa19-Lab4/blob/master/IMG_2510.jpg)

[My Design in Action](https://drive.google.com/open?id=1NVv9HleZR6zF_Bxx6z5VY4Yyxx3AAPdK)
 
