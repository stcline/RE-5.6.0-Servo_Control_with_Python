# How to run this code on your Raspberry Pi:

## Set up the circuit:
![The Python Demo Circuit](https://github.com/WHS-Robotics-Test-Org/Robotics_Engineering_Book/blob/master/Images/Python_demo.jpg)

## Prerequisites: 
    1. SSH connection to your Raspberry Pi (Using the Secure Shell App)
    2. Install Git on your Raspberry Pi (Should already be installed)

## How to execute code:
    1. `git clone https://github.com/stcline/Raspberry-Pi-LED-Blinking-in-Python`
    2. `cd Raspberry-Pi-LED-Blinking-in-Python`
    3. `sudo python main.py`
    
If everything is connected properly, your LED should be blinking slowly.  Feel free to mess around with the code a littel if you like.

## How to change GPIO pin:
    Change pin number in this line as per your requirements.
    `led = 12 # GPIO pin number is 12 and name is GPIO18`
