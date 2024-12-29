Project Overview

The Real-Time Navigation Aid (RTNA) is an innovative wearable device designed to assist visually impaired individuals in navigating their surroundings safely and efficiently. This system leverages the ESP32-CAM module for obstacle detection and provides auditory navigation cues via Bluetooth earpods. A mobile application enhances user experience by offering real-time updates and customization options.

Features

Real-Time Obstacle Detection: Utilizes the ESP32-CAM module to detect obstacles in the user's path.

Auditory Feedback: Delivers navigation cues through Bluetooth-connected earpods.

Custom Dataset Integration: A custom dataset created using Edge Impulse ensures accurate object detection.

Mobile App Integration: Allows users to configure settings and receive alerts.

Compact and Wearable Design: Ensures user comfort and ease of use.

Components

Hardware

ESP32-CAM module

Bluetooth earpods

Power supply

Software

Arduino IDE

Edge Impulse (for dataset generation)

Mobile application (for configuration and updates)

How It Works

Object Detection:

The ESP32-CAM captures real-time images and identifies obstacles using a pre-trained model.

Detected objects are displayed on the serial monitor during testing and debugging.

Auditory Feedback:

Detected objects are announced via Bluetooth earpods, guiding the user to avoid obstacles.

Mobile App Integration:

A dedicated mobile app allows users to customize settings and access additional features like navigation history.

Installation and Setup

Hardware Setup

Connect the ESP32-CAM module to your computer using a USB cable.

Ensure the power supply and Bluetooth earpods are properly configured.

Software Setup

Install the Arduino IDE.

Import the custom Edge Impulse dataset library into the Arduino IDE.

Deploy the program to the ESP32-CAM module.

Mobile App Setup

Download the RTNA mobile app.

Pair your device with the ESP32-CAM via Bluetooth.

Configure your preferences in the app settings.

Usage

Wear the device and turn it on.

Pair the Bluetooth earpods with the device.

Start the navigation process via the mobile app.

Receive real-time auditory feedback for obstacle detection and safe navigation.

Future Enhancements

Integration with GPS for outdoor navigation.

Enhanced object recognition using advanced AI models.

Additional haptic feedback for improved user interaction.

Acknowledgments

This project is part of a larger initiative to improve accessibility and independence for visually impaired individuals. Special thanks to the contributors and developers who made this possible.
