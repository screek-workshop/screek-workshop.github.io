---
comments: false
---

## 介绍

这是一款专门为HomeAssistant定制的人体24G雷达传感器，基于ESPHome固件定制，使用WIFI连接，采用通用的TYPE-C USB供电。  

## 产品特色

- WIFI直连，不需要任何网关。
- 使用ESP32-C3作为通信芯片，射频能力优秀，发热量低。
- ESPHome直接接入，只要完成配网之后，就直接可以在HomeAssistant中搜索设备。
- 1S版带有显示屏，能够直观的显示雷达工作状态，了解运行情况。

!!! info "版本区别"
    1W版除了没有显示屏之外，功能和1S是一样的。  

### 高级特色
- Type-C口除了作为供电，也能作为配网和恢复固件用。
- 能够插入电脑使用网页版的[ESPHome Web Tools](https://web.esphome.io/)来查看运行日志。