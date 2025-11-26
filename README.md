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
