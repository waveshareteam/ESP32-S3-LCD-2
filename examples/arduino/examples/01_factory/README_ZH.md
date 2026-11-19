# 综合诊断

[English](README.md) | [简体中文](README_ZH.md)

## 功能

在 LCD 上显示系统信息、QMI8658 读数、摄像头预览和 Wi-Fi 状态，使用 BOOT 按键导航。

## 硬件需求

- ESP32-S3-LCD-2 开发板和 USB 数据线
- 可选的 OV5640 摄像头、microSD 测试卡和 2.4 GHz Wi-Fi 测试网络（用于对应检查）

## 怎么运行

1. 在开发板管理器中安装 [仓库首页](../../../../README_ZH.md) 所列版本的 Arduino-ESP32。
2. 将项目文件夹位置设为 `examples/arduino/`，或将 [随附的库](../../libraries/) 复制到项目文件夹下的 `libraries` 目录。
3. 选择 **ESP32S3 Dev Module**，并按 [产品配置](../../../../.github/product.json) 设置「工具」菜单。
4. 打开本目录中的 `.ino` 文件并上传。

## 预期现象

使用 BOOT 按键操作。单击向下，双击向上，长按确认。

## 常见问题

测试 Wi-Fi 前，请在上传前将 `sta_ssid` 和 `sta_pass` 配置为测试网络的连接信息。WiFi 页面会在屏幕上显示这两个值。
