# BLE_OTA_PlatformIO_Script
A script for performing OTA update over BLE on ESP32
Modified from https://github.com/fbiego/BLE_OTA_Python

## Requirements
- [`Bleak`](https://github.com/hbldh/bleak)
 `$ pip install bleak`


## Usage
add 

`extra_scripts = bleota.py`

`upload_protocol = custom`

`MAC_ADDR = your device mac here`

in `platformio.ini`

and paste `bleota.py` near `platformio.ini`
