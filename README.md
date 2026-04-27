# ESP Camera Test

Code to test the ESP32 camera, based on the official Espressif repository, adapted for connecting and testing with Arduino.

## Folders

### `cameraweb_Server/`
Adapted version with MQTT support. Publishes the server IP on HiveMQ Cloud for remote access. Configured for the **AI-THINKER** camera model.

### `Sketch_06.1_CameraWebServer/`
Base version of the original code (Freenove). Simple version of the web server for initial camera testing.

## Usage

1. Select the camera model in `board_config.h` or in the `.ino` file
2. Configure WiFi credentials
3. Compile and upload to the ESP32
4. Access via web to the assigned IP

## Requirements

- ESP32 with camera
- `esp-camera` library
- Available WiFi
