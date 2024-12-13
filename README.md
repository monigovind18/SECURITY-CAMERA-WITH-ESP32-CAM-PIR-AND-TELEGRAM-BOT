# SECURITY-CAMERA-WITH-ESP32-CAM-PIR-AND-TELEGRAM-BOT
# tele_bot_secur_sys
SECURITY-CAMERA WITH ESP32 CAM, PIR AND TELEGRAM BOT

# Smart Security Camera

This project showcases a Smart Security Camera system that combines the ESP32-CAM, PIR sensor, and Telegram bot for an advanced home surveillance solution. The system dynamically captures images in response to detected motion, sending real-time alerts and images to a designated Telegram account. Users can interact with the system via Telegram commands, making it a versatile and customizable security solution.

## Table of Contents
- [Components Required](#components-required)
- [Software Required](#software-required)
- [Connections](#connections)
- [Program](#program)
- [Output](#output)
- [Advantages](#advantages)
- [Getting Started](#getting-started)
- [License](#license)

## Components Required
1. **ESP32-CAM**: 
   - Central processing unit with integrated camera and Wi-Fi for image capture and wireless communication.
   
2. **PIR Sensor**: 
   - Motion detection mechanism that triggers image capture upon detecting infrared radiation from moving objects.
   
3. **TTL Programmer**: 
   - Used for programming and interfacing with the ESP32-CAM.

## Software Required
- **Arduino IDE**: 
  - Used for programming and flashing the ESP32-CAM with the necessary code.
  
- **Telegram**: 
  - Messaging platform used for real-time communication and interaction with the security camera system.

### Arduino IDE Setup
- Install the ESP32 Board Support Package:
  - URL: `https://dl.espressif.com/dl/package_esp32_index.json`

### Create a Telegram Bot
- Install Telegram on your device.
- Search for "Bot Father" and create a new bot.
- Save the bot token for ESP32-CAM interaction.

## Connections
### ESP32-CAM to TTL Programmer:
- Connect the ESP32-CAM to the TTL programmer for uploading the code.

### ESP32-CAM to PIR Sensor:
- Interface the PIR sensor with the ESP32-CAM to enable motion detection and image capture.

## Program
- The Arduino IDE code can be found [here](https://1drv.ms/w/s!ApozpeoCVpJoozSRydbGtCI0gfda?e=DMAZew).
- Upload the code to the ESP32-CAM using the TTL programmer.

## Output
- The system captures and sends images to the designated Telegram bot upon motion detection.
- Users can control the system via Telegram commands like `/photo` for taking photos and `/flash` for toggling the LED.

## Advantages
- **Real-Time Notifications**: Instant alerts and images sent to Telegram upon motion detection.
- **User Interaction and Control**: Interact with the system via Telegram commands for real-time control.
- **Wireless Connectivity**: Built-in Wi-Fi for flexible camera placement.
- **Versatility and Integration**: Seamless integration with the PIR sensor and Telegram bot.
- **Cost-Effective Solution**: Affordable yet powerful home security solution.
- **Ease of Implementation**: Simplified development process using Arduino IDE.
- **IoT Integration**: Aligns with IoT principles for a smart home ecosystem.

## Getting Started
1. Clone this repository.
2. Set up the ESP32-CAM with the Arduino IDE.
3. Create and configure your Telegram bot.
4. Connect the hardware components as described.
5. Upload the code to the ESP32-CAM.
6. Start monitoring your environment with real-time updates via Telegram.

