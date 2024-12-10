# Distance-Perceptive Robot Project
This repository documents a robotic project that integrates Arduino Uno, C programming, and OpenSCAD-based 3D modeling. 
The robot is designed to autonomously travel forward until it detects a nearby wall, deposit a cube, and then return to 
its original starting position.

### Key Features
Autonomous Navigation: The robot uses a distance sensor to perceive its environment, stopping at a predefined proximity to a wall.
Cube Deployment: A servo-powered catapult mechanism drops a cube once the robot has reached the target position.
Return-to-Start Functionality: After placing the cube, the robot navigates back to its starting point.
Custom 3D-Printed Body: The chassis and structural components are designed using OpenSCAD, providing a fully customizable and lightweight frame.
Precise Motor Control: Servo motors (for both wheels and catapult) are driven by C code running on the Arduino microcontroller to ensure accurate movements.
