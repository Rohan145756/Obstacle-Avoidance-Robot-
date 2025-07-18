# Obstacle-Avoidance-Robot-
Obstacle Avoidance Robot Using NodeMCU with RemoteXY Control
This project is a 4-wheeled obstacle avoidance robot built using a NodeMCU (ESP8266) microcontroller, L298N motor driver, and ultrasonic sensor for distance measurement. The robot is powered by a 12V power supply and is remotely controlled through the RemoteXY mobile application using a WiFi access point mode.



🔧 Key Components:
NodeMCU (ESP8266) – Microcontroller for controlling logic and communication.

L298N Motor Driver – Controls the four DC motors (2 on each side) for robot movement.

Ultrasonic Sensor (HC-SR04) – Measures distance to detect obstacles.

RemoteXY App – Provides a WiFi-based interface to control the robot using 4 directional buttons (Forward, Reverse, Left, Right).

12V Power Supply – Powers the motors and NodeMCU via regulated supply.



🚀 Working Principle:
WiFi Communication:

The NodeMCU acts as a WiFi Access Point using the SSID "Car" and password "12345678".

RemoteXY mobile app connects to this access point to send movement commands.

Movement Control:

The RemoteXY interface has 4 buttons for directions.

When a button is pressed, the corresponding motor pins are activated to move the robot in the desired direction.

Pin connections:

in1, in2 → Left Motor

in3, in4 → Right Motor



Obstacle Avoidance Logic:

The ultrasonic sensor (Trig: D1, Echo: D2) continuously measures the distance in front of the robot.

If the forward button is pressed and the path is clear (distance ≥ 30 cm), the robot moves forward.

If an obstacle is detected (distance < 30 cm), the robot stops or waits for another command.



Movement Functions:

forward() – Moves both motors forward.

reverse() – Moves both motors backward.

clockwise() – Right turn (left motor forward, right motor backward).

anticlock() – Left turn (left motor backward, right motor forward).

stop() – Stops all motors.



📱 RemoteXY Interface:
A GUI is created using RemoteXY's visual designer.

The interface includes 4 buttons mapped to movement functions.

NodeMCU handles the command inputs and processes them accordingly.
