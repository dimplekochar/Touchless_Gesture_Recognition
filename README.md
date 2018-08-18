# Touchless_Gesture_Recognition
In this project, Harsh and I set to first recognize a gesture (without usage of arduino or any microcontroller). 
First we ideated and simulated on how can we bring about the project. that can be seen in the Simulation Report.

Finally, we constructed an analog circuit, using 4 TCRT5000 ICs. A pair of these IR sensor-receiver pairs can detect two gestures - forward and backward. So, now comes the decoding the gesture. Even though this project was done for our Analog Lab, we ended up using skills from our Digital Lab; from the Altera Quartus software to the Krypton CPLD board. Coding in VHDL, we were successfully able to implement gesture recognition to 3 applications:
1) A tracker. Using an 8x8 LED matrix, on making say, a forward swipe, the LED next to that currently lit would light up and the previous one go off. In this way, we could keep track of motions visually.
2) A touchless gesture lock. Code your desired pattern and the lock would unlock (or unlocked lock lock) only if the correct gesture is made.
3) Audio volume control. Using simple gesture swipes, you can increase/decrease the volume of any song being played, even using your mobile phone.
