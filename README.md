# muneeb-abbas
Personal Engineering portfolio with Arduino Projects, embedded systems work, and university projects.

1  - Autonomous Collision Avoidance Vehicle (Arduino-Based)

This project is an Arduino-based autonomous vehicle that can detect obstacles and intelligently navigate around them. It uses an ultrasonic sensor mounted on a servo to scan the environment and make real-time decisions on movement.

## Overview
- Built using the Elegoo Smart Car V3 platform
- Uses a servo-mounted ultrasonic sensor for 180° environmental scanning
- Implements logic to:
  - Move forward by default
  - Stop when an object is detected within 40 cm
  - Turn left or right based on which direction is clearer
  - Resume forward motion

## Components Used
- Arduino Uno (Elegoo Smart Car V3)
- Ultrasonic Sensor (HC-SR04)
- Servo Motor
- L298N Motor Driver
- Breadboard and jumper wires
- Arduino IDE

## Skills and Concepts Applied
- Embedded C++ programming
- Real-time sensor data handling
- Servo control and PWM motor driving
- Conditional logic and obstacle detection
- Circuit design and troubleshooting

## Demo

## Potential Improvements
- Add line-following capabilities using IR sensors
- Integrate Bluetooth or RF control modes
- Potentially a configuration setting prior to the car running to choose between autonomously moving or remote control

## Contact
Created by **Muneeb Abbas**
Email: muneebabbas1998@gmail.com  
