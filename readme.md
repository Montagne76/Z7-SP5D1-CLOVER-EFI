# 简介

这是神舟 Z7-SP5D1 黑苹果的 EFI 配置（单盘双系统）

## 电脑配置

| 规格     | 详细信息                                     
| --- | ---
| 电脑型号 | 神舟 Z7-SP5D1
| SystemModel | P65xRP
| 处理器          | 英特尔 酷睿 i5-6300hq 处理器  
| 核显 | Intel(R) HD Graphics 530
| 独显 | GeForce GTX 1060 (6 GB)
| 声卡     | Realtek ALC892
| 网卡     | Intel(R) Dual Band Wireless-AC 3165
| BIOS               | 1.05.03(type：UEFI)


## 工作的部分

- 核显
- 独显 HDMI 输出（可外接显示器）
- 触控板
- 声音
- 蓝牙连接
- 无线网络
- 电池电量显示

## 安装准备
| 类型     | 详细信息
| --- | ---
|macOS 镜像|[【黑果小兵】macOS High Sierra 10.13.6(17G65) Installer with Clover 4596.dmg](https://blog.daliansky.net/macOS-High-Sierra-10.13.6-17G65-Release-Version-with-Clover-4596-original-mirror.html "【黑果小兵】macOS High Sierra 10.13.6(17G65) Installer with Clover 4596.dmg")
|EFI 分区|>=300MB
|硬盘| GPT
|BIOS|  UEFI
|U盘|>=8G，后续会被格式化，请先保存数据
|写盘工具|Transmac
|添加引导|EASYUEFI
|分区工具|Diskgenius
|显卡驱动|[WebDriver-387.10.10.10.40.105_macOS High Sierra 10.13.6 (17G65).pkg](https://drivers.softpedia.com/get/GRAPHICS-BOARD/NVIDIA/NVIDIA-Quadro-GeForce-Graphics-Driver-387-10-10-10-40-105-macOS-High-Sierra.shtml "WebDriver-387.10.10.10.40.105_macOS High Sierra 10.13.6 (17G65).pkg")，macOS 中安装
|WiFi客户端|[HeliPort_v1.4.1.dmg](https://github.com/OpenIntelWireless/HeliPort "HeliPort_v1.4.1.dmg")，配合 [itlwn](https://github.com/OpenIntelWireless/itlwm "itlwn") 驱动 WiFi，macOS 中安装
