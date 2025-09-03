# Pixer Uploader (Modified Version)

This project is based on [kasperis7/pixer](https://github.com/kasperis7/pixer).  
The original functionality was to upload images to the G+ Pixer e-ink photo frame.  
This modified version keeps the image upload feature and adds **firmware update** capability.

---

## Features
- Upload images to the device  
- Supported formats: `.jpg`, `.png`  
- **New:** Firmware upgrade functionality (BLE/ITE/BSP)  

---

## Usage

### 1. Executable file (.exe)
```bash
upload.exe test.jpg
```

### 2. Python script
```bash
python upload.py test.jpg
```

---

## Requirements (for Python version)
- Python 3.8+
- Required package:
  ```bash
  pip install pillow
  ```

---

## Changes
- Added firmware update process: supports updating `ble.bin`, `pixer.bin`, etc.  
- Improved error messages for easier debugging  
- Preserved the original image upload workflow  

---

## Reference
- [kasperis7/pixer](https://github.com/kasperis7/pixer)
