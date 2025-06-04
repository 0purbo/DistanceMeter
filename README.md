# DistanceMeter

# 📏🔊 DistanceMeter - Ultrasonic Distance Sensor with LCD Display

Welcome to **DistanceMeter**! This beginner-friendly Arduino project uses the HC-SR04 ultrasonic sensor to measure distance and shows the result on an I2C LCD. Perfect for anyone learning about sensors, Arduino programming, and LCD interfacing. 🚀

---

## 🛠️ Hardware Required

- Arduino Uno (or compatible board)
- HC-SR04 Ultrasonic Distance Sensor
- I2C 16x2 LCD Display (address: 0x27)
- Jumper wires
- Breadboard (optional)

---

## 🔌 Wiring Instructions




## 💻 Uploading The Code
Connect your Arduino to your computer via USB.
Open the Arduino IDE.
Create a new sketch and copy the provided code into the IDE.
Select your Arduino board from Tools > Board.
Select the correct port under Tools > Port.
Click the Upload button (right arrow icon).
Wait for the code to compile and upload.



## 🚀 How To Use
Once powered, the Arduino will read distance from the HC-SR04 sensor.
The measured distance (in centimeters) will be displayed on the LCD screen.
Distance values will also be printed in the Serial Monitor for debug purposes.
If no object is detected, the LCD will show "No Object Detected".


## 🎯 Learning Objectives
Understand how ultrasonic distance sensing works.
Practice wiring sensors and I2C LCD displays.
Learn to use Arduino's pulseIn() function for timing.
Display dynamic data on an LCD.
Serial debugging skills.

## 📃 License
This project is open source and free to use. Feel free to modify and share!

Happy coding! ✨👨‍💻👩‍💻
