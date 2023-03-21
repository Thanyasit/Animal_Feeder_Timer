# Automatic Animal Feeder
<h2>Description</h2>
This program controls an automatic animal feeder that dispenses food at specific intervals. The program uses an Arduino board, a servo motor, and a liquid crystal display (LCD) to control the feeder.<br>
<b>Project at Tha Luang Cement Thai Anusorn Technical College (2017)</b>
<h2>Installation</h2>
To use this program, you will need an Arduino board and the following libraries:<br><br>

- Wire.h<br>
- Servo.h<br>
- LiquidCrystal_I2C.h<br>

Download the code and upload it to your Arduino board using the Arduino IDE.
<h2>Usage</h2>
The program has two buttons: one for setting the feeding time and another for starting the feeding cycle. To set the feeding time, press the "Set" button and use the other button to increase the time. Once you have set the feeding time, press the "Start" button to begin the feeding cycle.

During the feeding cycle, the LCD displays the remaining time in hours, minutes, and seconds. When the time runs out, the program activates the servo motor to dispense the food.
<h2>License</h2>
This code is licensed under the MIT License. See the LICENSE file for details.
