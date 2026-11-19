# Button-controlled backlight

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Maps the BOOT button to an LVGL slider that sets the LCD backlight level by PWM.

## Hardware Required

- ESP32-S3-LCD-2 development board and USB data cable

## How to Run

Open an ESP-IDF terminal in this directory using a version listed in the [repository README](../../../README.md).

```bash
idf.py set-target esp32s3
idf.py build flash monitor
```

## Expected Result

Press BOOT briefly to lower the brightness or hold it to raise the brightness. The slider and percentage update with each change.

## Troubleshooting

None yet.
