# Sean's WS2812B LED Driver Package

## 简介
本软件包由 Sean 编写，用于通过 SPI 驱动 WS2812B RGB 灯带，适用于 RT-Thread。

## 特点
- SPI接口驱动，简单易用
- 支持Kconfig配置LED数量、SPI总线、SPI设备名、SPI引脚
- 支持Gamma矫正，亮度调节
- 示例程序可选

## 使用
通过`menuconfig`开启和配置后，即可在应用程序中调用 `sean_ws2812b_xxx` 系列API控制灯带。

## License
MIT License
