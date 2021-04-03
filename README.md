# hackintosh-lenovo-y700
Fully functional configuration for Hackintosh on Lenovo Y700

## What does work

### Hardware
- WiFi (Intel Dual Band AC-3165) - altough ~3Mbit/s
- Ethernet
- Touchpad & Keyboard
- Battery
- Camera
- Microphone
- USB3.0 & USB2.0
- Speakers
- iGPU (HD 530) Acceleration (2GB VRAM)

### Software
- Sleep, Wake & Shutdown
- Touch gestures
- All Apple services
- Battery level indicator
- Siri
- Display Brightness regulation
- Screen Mirroring (tested with LG)

## What does not work

### Hardware
- HDMI connector - might be possible to fix as it is not wired to dGPU
- Bluetooth - altough it is discovered in system and attempts to pair with smartphone
- dGPU (GTX960M) - and will not work, as MacOS dropped any support for that
- Subwoofer (it works only in Windows)

### Software
- Most likely Boot Camp & Parallels (altough not tested)


## Installation
Copy EFI directory to your EFI partition as is.
