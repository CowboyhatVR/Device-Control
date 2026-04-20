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

## Installation (Windows 11)

Follow these steps to build and install the app on your Flipper Zero.

---

### 1. Install Python

1. Download Python from:
   https://www.python.org/downloads/windows/

2. Run the installer

3. IMPORTANT:
   ✔ Check **"Add Python to PATH"**
   ✔ Click **Install Now**

4. After installation, open Command Prompt and check:

   ```bash
   python --version

   You should see a version like:

Python 3.x.x
2. Install uFBT (Flipper build tool)

In Command Prompt, run:

pip install --upgrade ufbt

If you get a PATH warning, you can still continue.

3. Download this project

Either:

Download ZIP from GitHub and extract it
or
Clone it:
git clone https://github.com/YOURNAME/device-control-flipper.git
4. Open the project folder

Example:

cd Desktop\device_control

(Use your actual folder path if different)

5. Build the app

Run:

python -m ufbt

If successful, you will get:

```dist\device_control.fap```
6. Copy to Flipper Zero
Connect your Flipper via USB
Open the SD card (via qFlipper, file explorer or [Flipper Lab](https://lab.flipper.net/))
Go to:
/ext/apps/Tools/
Copy:
```device_control.fap```
7. Run the app

On your Flipper:

Apps → Tools → Device Control

# Troubleshooting
"python not recognized"
Reinstall Python
Make sure "Add to PATH" is checked [x]
"ufbt not found"

### Run:

```python -m ufbt```

## Build errors:
Make sure you're inside the project folder
Check that ```device_control.c```and ```application.fam``` exist
