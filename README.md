# 3W RGB LED Driver

A custom-designed 3W RGB LED driver board with PWM dimming capability, developed for an Autonomous Underwater Vehicle (AUV).

## Overview

This board was designed to control the color output of a 3W RGB LED by adjusting each channel independently via PWM signals. The primary purpose is to support the AUV's image processing system by providing tunable, high-intensity underwater illumination.

## Features

- 3W RGB LED driving capability
- Independent PWM dimming for red, green, and blue channels
- Designed for underwater AUV integration
- Supports color-based object detection for computer vision tasks
- Tunable illumination for different underwater visibility conditions

## Use Case

Underwater visibility is limited, and colors can shift significantly with depth. By dynamically adjusting the RGB LED channels using PWM, the AUV's camera can capture more consistent color data.

This improves the reliability of image processing and object detection algorithms in underwater environments.

## Hardware

- **LED Type:** 3W RGB LED
- **Control Method:** Independent PWM dimming
- **Channels:** Red, green, and blue
- **Application:** Autonomous Underwater Vehicle lighting system
- **Purpose:** Image processing and object detection support

## Images

### PCB Front

![PCB Front](pcb_front.jpeg)

### PCB Back

![PCB Back](pcb_back.jpeg)
