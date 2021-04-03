# hackintosh-lenovo-y700
Fully functional configuration for Hackintosh on Lenovo Y700

## Current Version: Big Sur 11.2.3

## What does work

### Hardware
- WiFi (Intel Dual Band AC-3165) - although ~3Mbit/s
- Ethernet
- Touchpad & Keyboard
- Battery
- Camera
- Microphone
- USB3.0 & USB2.0
- Speakers
- iGPU (HD 530) Acceleration (2GB VRAM)
- HDMI connector (external Display) with Audio

### Software
- Sleep, Wake & Shutdown
- Touch gestures
- All Apple services
- Battery level indicator
- Siri
- Display Brightness regulation
- Screen Mirroring (tested with LG)
- Parallels

## What does not work

### Hardware
- Bluetooth - although it is discovered in system and attempts to pair with smartphone
- dGPU (GTX960M) - and will not work, as MacOS dropped any support for that
- Subwoofer (it works only in Windows)


## Installation
Copy EFI directory to your EFI partition as is.
