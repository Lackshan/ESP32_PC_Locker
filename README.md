# ESP32 PC Locker
Simple project that uses an ESP32 to detect when your phone (or any BLE device) moves away from your PC and locks it.

# Requirements
## ESP32
Arduino IDE
Install esp32 board support (https://docs.espressif.com/projects/arduino-esp32/en/latest/installing.html)

## PC
Python X.X.X

# Architecture
## ESP32

## PC
The python script opens a serial connection to the ESP32 and waits for a departure notification after which it locks the PC.

# Usage
## ESP32
Flash the project in the ESP32 directory.

## PC
Run the Python script in the PC directory.


