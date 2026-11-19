# LVGL 音乐播放器界面

[English](README.md) | [简体中文](README_ZH.md)

## 功能

在板载 LCD 上显示 LVGL 音乐播放器演示界面。

## 硬件需求

- ESP32-S3-LCD-2 开发板和 USB 数据线

## 怎么运行

1. 在开发板管理器中安装 [仓库首页](../../../../README_ZH.md) 所列版本的 Arduino-ESP32。
2. 将项目文件夹位置设为 `examples/arduino/`，或将 [随附的库](../../libraries/) 复制到项目文件夹下的 `libraries` 目录。
3. 选择 **ESP32S3 Dev Module**，并按 [产品配置](../../../../.github/product.json) 设置「工具」菜单。
4. 打开本目录中的 `.ino` 文件并上传。

## 预期现象

LCD 显示专辑封面和播放器控件。Arduino 示例开启了自动播放动画。

## 常见问题

如果编译器找不到 `lv_demo_music`，请使用仓库中带有演示源码的 LVGL 库。
