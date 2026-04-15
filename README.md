# Scoutag
A portable ESP32 device that scans for evil twin WiFi attacks, with an animated dog mascot on a ST7789 TFT display.

## Hardware
ESP32<br>
ST7789 SPI TFT 170×320px<br>
DFRobot MP2636 Power Booster & Charger<br>
LiPo battery<br>
Tactile button (GPIO 0)<br>

## Controls
Hold 2 seconds---
Power ON<br>
Short press---
Start WiFi scan<br>
Hold 2 seconds (while on)---
Power OFF<br>


## How it works
Scans nearby networks and compares them in pairs. Flags suspicious matches based on:
Similar SSID name
Nearly identical MAC address
Open (no) encryption
Unusually strong signal
Non-standard channel
Results are shown on screen with a threat score. Higher score = more suspicious.
