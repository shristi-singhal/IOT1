# Smart Street Light IoT Project
## Overview:

A smart street lighting solution using Arduino, IR sensors, LDR, and LEDs. The system detects day/night, senses motion, and adjusts light intensity to conserve energy and enhance road safety.

## Features:

- **Day/Night Detection:** LDR sensor automatically keeps street lights OFF during daytime and activates them only at night.
- **Motion-Based Lighting:** IR sensors detect vehicles or pedestrians.
- **Dynamic Light Control:** At night, lights remain dim with no activity. When motion is detected, LEDs increase from dim to bright. Once the moving object passes, lights revert to dim state.
- **Energy Conservation:** Reduces unnecessary illumination.

## Hardware Used:

- Arduino UNO
- IR Sensors
- LDR (Light Dependent Resistor)
- LEDs
- Breadboard, wires, and model base

## How It Works:

1. LDR senses ambient light:
   - **Day:** All street lights OFF.
   - **Night:** System activates; lights operate in dim or bright mode.
2. IR sensor detects motion:
   - **No Motion (Night):** LEDs stay dim.
   - **When Motion Detected:** LEDs brighten; when vehicle passes, LEDs return to dim.
3. Arduino coordinates sensor input to control lighting seamlessly.

## Applications:

- Smart cities and sustainable infrastructure
- Adaptive urban lighting with real-time energy management
- Road safety enhancement.



-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------


# Gesture & Mood Swing Wi-Fi Robotic Car(PHOTO)

## Overview:

This project showcases a robotic car controlled over Wi-Fi via ESP32, combining gesture recognition with the MPU6050 sensor and mood swing inputs from the Blynk mobile app. The integration demonstrates advanced, user-friendly robotics powered by IoT technology.

## Features:

- **Gesture-Based Control:** Use the MPU6050 accelerometer/gyroscope sensor to interpret specific hand movements as car control commands (e.g., forward, reverse, left, right).
- **Mood Swing Detection via Blynk App:** Mood is selected or sensed through interactive widgets in the Blynk app dashboard, influencing car response (e.g., driving style, speed, lighting).
- **Wi-Fi Communication:** ESP32 acts as the core IoT controller, processing sensor and app signals in real time.
- **Embedded Programming:** C/C++ code for seamless hardware-software integration.

## Hardware Used:

- ESP32 Wi-Fi microcontroller
- MPU6050 accelerometer/gyroscope (gesture detection)
- L298N motor driver
- DC motors and chassis kit
- Battery pack
- Breadboard, jumper wires

## How It Works:

- **Gestures:** The user’s hand motions are captured by the MPU6050 and transmitted to the ESP32, controlling movement and direction of the car.
- **Mood Swings:** The Blynk app dashboard allows the user to input their mood (e.g., happy, calm, excited) or use sensors connected to ESP32 to dynamically sense mood. The car adapts its behavior accordingly—such as changing speed or LED color.
- **Wireless Control:** All signals are processed in real-time via Wi-Fi, allowing remote and intuitive operation.

## Applications:

- Interactive robotics and IoT demonstrations
- Prototype for smart assistive vehicles and emotional interfaces
- Educational use in embedded systems, IoT, and user interface design

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Joystick-Controlled Wi-Fi Robotic Car (Blynk App)(VIDEO)

## Overview:

This project implements a basic robotic car controlled over Wi-Fi using an ESP32 (or ESP8266). The car’s directions and movement are operated in real-time through a virtual joystick on the Blynk mobile app, enabling wireless, intuitive remote driving.

## Features:

- Real-time car control over Wi-Fi
- Direction and speed manipulation with the Blynk app’s joystick widget
- Embedded hardware with DC motors and motor driver
- Clean, beginner-friendly IoT demonstration

## Hardware Used:

- ESP32 or ESP8266 microcontroller
- L298N motor driver
- DC motors & car chassis kit
- Battery pack & wires
- Breadboard (if required)

## How It Works:

- The Blynk mobile app is set up with a project featuring the Joystick widget.
- The joystick sends movement commands (forward, reverse, left, right, speed) to the ESP32/ESP8266 via Wi-Fi.
- The microcontroller interprets these commands and controls the motor driver accordingly.
- User enjoys wireless, responsive driving from their phone.

## Applications:

- Demonstrates basics of wireless robotics and IoT
- Fun remote-controlled vehicle for STEM education and DIY projects
- Entry point for mobile-based embedded system development


