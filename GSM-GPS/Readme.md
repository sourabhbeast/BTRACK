# A9G GSM GPS SOS Communication System using ESP32 Xiao (C3) 📞🌍

The A9G GSM GPS SOS Communication System is a project designed to integrate the A9G GSM GPS module with an ESP32 Xiao (C3) board for sending SOS messages or making SOS calls. This project is intended for emergency situations where a button press triggers the communication system to send alerts along with GPS coordinates to a predefined contact. 🚨📡🛰️

## Features 🌟

- Sends SOS messages or makes SOS calls to a predefined contact number, including GPS coordinates. 📲🌍
- Utilizes the A9G GSM GPS module for combined GSM and GPS functionality. 📡🛰️
- Integrates the ESP32 Xiao (C3) board for control and communication. 💻
- Designed for quick communication and location sharing in emergency scenarios. ⏱️🌍
- Power-saving features by optimizing module usage and sleep modes. 🔋
- Customizable SOS button press duration, contact number, and other parameters. ⏰🔧
- Provides status updates and responses via serial communication. 📟

## Requirements 🛠️

- Arduino IDE (Integrated Development Environment) 💻
- ESP32 Xiao (C3) board 📟
- A9G GSM GPS module 📡🛰️
- Appropriate connections and components (button, resistors, etc.) 🔌

## Setup ⚙️

1. Open the Arduino IDE.
2. Connect the ESP32 Xiao (C3) board and A9G GSM GPS module along with necessary components according to the schematic.
3. Modify the code to set the SOS button pin, GPS configuration, SOS contact number, and other parameters if necessary.
4. Upload the code to the ESP32 Xiao (C3) board.
5. Open the Serial Monitor to view status updates, responses, and debugging information.

![Battery side](https://github.com/Shanvimathuriaa/BTRACK/assets/143255481/23c4cd60-cb0f-499e-a86a-c43e518214ae)

![Esp 32 side](https://github.com/Shanvimathuriaa/BTRACK/assets/143255481/0d6edf33-d12c-45aa-97fd-ed698b311397)
 

## Usage 🚀

1. Power on the ESP32 Xiao (C3) board with the integrated A9G GSM GPS module.
2. Press and hold the SOS button for the specified duration (default: 5 seconds).
3. The system will send an SOS message or initiate a call to the predefined contact number, including GPS coordinates.
4. Monitor the Serial Monitor for status updates, responses, and GPS location information.

## Note 📝

- Make sure to test the system thoroughly in a controlled environment before relying on it in actual emergencies.
- This project assumes that you have basic knowledge of Arduino programming and circuit connections. 💡
- Ensure the A9G GSM GPS module has a clear view of the sky for optimal GPS performance.
