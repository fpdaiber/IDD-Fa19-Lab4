# Paper Puppets

*A lab report by Fabio Daiber*

## In this Report

To submit your lab, clone [this repository](https://github.com/FAR-Lab/IDD-Fa18-Lab4). You'll need to describe your design, include a video of your paper display in operation, and upload any code you wrote to make it move.

## Part A. Actuating DC motors

**Link to a video of your virbation motor**

## Part B. Actuating Servo motors

### Part 1. Connect the Servo to your breadboard

**a. Which color wires correspond to power, ground and signal?**

Red corresponds to power, orange to signal an brown to ground.

### Part 2. Connect the Servo to your Arduino

**a. Which Arduino pin should the signal line of the servo be attached to?**

We have to connect it to pin 9 or change ```myservo.attach(9);```

**b. What aspects of the Servo code control angle or speed?**

The angle is controlled by this part of the code ```pos = 0; pos <= 180; pos += 1```and to corresponding part ```pos = 180; pos >= 0; pos -= 1```
There is two ways to change the speed. We can simply change the  ```delay(1); ``` function or we can change the position increments: ```pos += 1```


## Part C. Integrating input and output

**Include a photo/movie of your raw circuit in action.**

![alt text]()

I changed the delay function to read-in value of the potentiometer on pin 0, so I can control the speed of the servo.

[My custom code]

## Part D. Paper puppet

**a. Make a video of your proto puppet.**

## Part E. Make it your own

**a. Make a video of your final design.**
 
