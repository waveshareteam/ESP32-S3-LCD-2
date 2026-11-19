# 用 BOOT 按键调节背光

[English](README.md) | [简体中文](README_ZH.md)

## 功能

将 BOOT 按键映射到 LVGL 滑块，并通过 PWM 调节 LCD 背光。

## 硬件需求

- ESP32-S3-LCD-2 开发板和 USB 数据线

## 怎么运行

使用 [仓库首页](../../../README_ZH.md) 所列版本的 ESP-IDF，在本目录中打开 ESP-IDF 终端。

```bash
idf.py set-target esp32s3
idf.py build flash monitor
```

## 预期现象

短按 BOOT 降低亮度，长按 BOOT 提高亮度。屏幕上的滑块位置和亮度百分比随之变化。

## 常见问题

暂无。
