# Smart-voice-hub
# Voice-Controlled Bluetooth Home Automation

A Python-based project to control smart home devices using voice commands and Bluetooth (via serial communication).

## Features
- Voice recognition using a microphone
- Device control using pyserial over Bluetooth
- Simple and extensible Python code
- Works with HC-05, HC-06, and ESP32 (serial)

## Requirements

```bash
pip install SpeechRecognition pyserial pyaudio
```

## Setup
1. Pair your Bluetooth device (e.g., HC-05) with your PC.
2. Find the COM port from Device Manager.
3. Update the COM port in `device_controller.py`.
4. Run the app:
```bash
python main.py
```

## Usage
Speak commands:
- "Turn on the light"
- "Turn off the fan"

These will be sent via Bluetooth to your device.

## License
MIT License
