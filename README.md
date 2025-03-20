# Raspberry Pi Zero Walkie-Talkie

This project allows communication between a Raspberry Pi Zero 2 W and a webpage using WebRTC. The Pi Zero acts as a walkie-talkie that streams audio to the webpage, where you can hear it through a push-to-talk button.

## Features
- Real-time, low-latency audio streaming.
- Hosted webpage with a **Hold to Talk** button.
- Pi Zero streams audio using WebRTC.

## Requirements
- Raspberry Pi Zero 2 W with a **Logitech USB headset**.
- **Internet access** for both devices (Pi Zero and the webpage).
- **GitHub Pages** for hosting the webpage.
- Python libraries: `pyaudio`, `aiortc`.

## Setting Up the Pi Zero
1. Install dependencies:
   ```bash
   sudo apt update
   sudo apt install python3-pip python3-pyaudio
   pip3 install aiortc
