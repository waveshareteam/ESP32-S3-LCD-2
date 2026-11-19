# Button-controlled backlight

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Maps the BOOT button to an LVGL slider that sets the LCD backlight level by PWM.

## Hardware Required

- ESP32-S3-LCD-2 development board and USB data cable

## How to Run

1. Install the Arduino-ESP32 board package version listed in the [repository README](../../../../README.md).
2. Set the sketchbook location to `examples/arduino/`, or copy the [bundled libraries](../../libraries/) into the sketchbook's `libraries` folder.
3. Select **ESP32S3 Dev Module** and apply the options in the [product configuration](../../../../.github/product.json).
4. Open the `.ino` file in this folder and upload.

## Expected Result

Press BOOT briefly to lower the brightness or hold it to raise the brightness. The slider and percentage update with each change.

## Troubleshooting

None yet.
