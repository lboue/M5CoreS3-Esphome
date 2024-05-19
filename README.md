# M5CoreS3 ESPhome voice assistant

## Prerequisites

- Home Assistant 2023.12 or later, installed with the Home Assistant Operating System. If you do not have Home Assistant installed yet, refer to the [installation page](https://www.home-assistant.io/installation/) for instructions.
- [Home Assistant Cloud](https://www.home-assistant.io/voice_control/voice_remote_cloud_assistant/) or a manually configured [Assist Pipeline](https://www.home-assistant.io/voice_control/voice_remote_local_assistant)
- Your 2.4 GHz Wi-Fi network password
- Chrome or Edge browser on a desktop (not Android/iOS)
- One [M5Stack CoreS3](https://shop.m5stack.com/products/m5stack-cores3-esp32s3-lotdevelopment-kit) development kit
- USB-C cable to connect the ESP32-S3-BOX

## Installing the software onto the CoreS3

* Create a new device in ESPhome
* Edit the device
* Copy data from [m5stack-cores3.yaml](/voice-assistant/m5stack-cores3.yaml) file into you new device
* Replace Home Assistant API key with your own
* Replace WiFi SSID and password with your own
* Install on your device
