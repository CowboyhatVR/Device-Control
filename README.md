# Device Control (Flipper Zero)

A simple and responsive tool to control LED and haptic feedback on the Flipper Zero.

## Features

### LED
- Red, Green, Blue
- Yellow, Purple, Cyan, White (via RGB combinations)
- Rainbow mode
- Hold mode (keep LED on without holding the button)

### Haptics
- Hold OK to vibrate
- Instant response (no delay)

### Party Mode
- Dynamic LED color cycling
- Rhythmic vibration patterns
- Designed to feel varied, not repetitive

---

## Controls

### Main Menu
- Up / Down → Navigate
- OK → Select
- Back → Exit

### LED Menu
- OK → Activate LED
- Hold OK → Temporary light (when Hold mode is OFF)
- Left / Right → Toggle Hold mode

### Haptics
- Hold OK → Vibrate
- Release → Stop instantly

### Party Mode
- Runs automatically
- Back → Exit

---

## Installation

Build the app:
```bash
python -m ufbt

Copy the .fap file to:

/ext/apps/Tools/

Run it on your Flipper Zero.

Project Structure
device_control/
├── device_control.c
├── application.fam
├── icon.png
└── README.md
Notes
Built using Flipper Zero SDK (ufbt)
Focused on responsiveness and simplicity
Author

CowboyHatVR
