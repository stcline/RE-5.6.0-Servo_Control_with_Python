# :robot: Raspberry Pi Lab - Servo Control

## 🤓 Overview and learning outcomes 

## Lab Setup

### Electronics Components

You will need the following components from your kit for this assignment:
<ul>
  <li>Raspberry Pi</li>
  <li>Several Jumper Wires (see diagrams below)</li>
  <li><a href = "https://www.robotshop.com/media/catalog/product/cache/image/1350x/9df78eab33525d08d6e5fb8d27136e95/h/i/hitec-hs422-servo-motor-13.jpg" target = "_blank">HiTec Servo</a></li>
</ul>

### Prototpypes
Construct the prototype using the diagram below:

![The Servo Circuit](https://github.com/WHS-Robotics-Test-Org/Robotics_Engineering_Book/blob/master/Images/servo_control.JPG)

### Procedure: Code Execution

- Prerequisites: 

    1. SSH connection to your Raspberry Pi (Using the Secure Shell App)
    2. Install Git on your Raspberry Pi (Should already be installed)

- Get the code and run the script:

    `git clone https://github.com/stcline/RPi_Lab-Servo-Control`
    
    `cd RPi_Lab-Servo-Control`
    
    `sudo python main.py`
    
If everything is connected properly, your servo should be moving through several positions.  Feel free to mess around with the code a little if you like.

## Further learning:
    To learn more, try this video:
[![Alt text](https://img.youtube.com/vi/ZgURwWJaOZw/0.jpg)](https://www.youtube.com/watch?v=ZgURwWJaOZw)
    
A more detailed and complex application for a servo may be found [here](https://makersportal.com/blog/2020/3/21/raspberry-pi-servo-panning-camera).
    
## 📝 Next steps (Graded)

Now that you know how the sensor runs and can see how some of the code works, answer the following questions.  Save them in a markdown file in this repo named, "questions.md".  Create a pull request when you are all done to let me know it is ready to grade.

### Questions:

1. In what various ways does the servo behave differently than a DC motor?
2. What makes the use of a servo more complex (remember that if you were controlling a DC motor with a Pi, you would need to write some code)?
3. What applications do you thin servos are appropriate for?  Explain.

## 📚  Resources 

[SparkFun Electronics - Servos Explained](https://www.sparkfun.com/servos)
