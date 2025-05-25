
# ElectroBlocks Arduino Uno Demos using Python

This repository contains Jupyter Notebook examples demonstrating how to control Arduino Uno  using the ElectroBlocks Python generated code
## 📦 Prerequisites

- Arduino Uno
- ElectroBlocks firmware uploaded to Arduino
- Python 3.8+ installed
- Jupyter Notebook

## ⚙️ Installation Steps

1. Install Python and Jupyter (if not installed):
   ```bash
   pip install notebook

## ✅ `firmware_upload_steps.md`


# Firmware Upload Instructions for ElectroBlocks

To use the ElectroBlocks Python library, you must upload its firmware to your Arduino Uno board.

## 🔧 Requirements

- Arduino Uno board
- Arduino IDE installed (https://www.arduino.cc/en/software)
- USB cable

## 📥 Step-by-Step Instructions

1. **Open Arduino IDE**

2. **Download ElectroBlocks firmware**
   - Go to: https://github.com/ElectroBlocks/python
   - Download the firmware file located in `arduino/` directory.

3. **Open firmware file  in Arduino IDE**

4. **Connect your Arduino Uno**
   - Go to `Tools > Board` and select **Arduino Uno**
   - Go to `Tools > Port` and choose the correct COM port

5. **Upload the Sketch**
   - Click the ✅ Verify button to compile
   - Click the ➡️ Upload button to upload the firmware

6. **Once uploaded, close the Arduino IDE**
   - This frees up the port for use with Python

## ✅ Your Arduino is now ready to be controlled using Python!
