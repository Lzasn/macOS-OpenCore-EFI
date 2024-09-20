![OpenCore_with_text_Small](https://github.com/user-attachments/assets/49f199f8-6059-4386-bd19-5c7eabf65c29)


## macOS OpenCore EFI

>  [!CAUTION]
>
>  本仓库仅用于存放OpenCore的相关文件，不承担因使用了此仓库下载EFI引导文件导致的引导失败、功能异常（缺失）、系统运行异常以及一切均与所有者无关的问题

> [!NOTE]
>
> 如果你的电脑硬件配置和我上传的EFI引导所使用的硬件配置很相似，那么你可以尝试能不能正常使用，否则请自行生成EFI并根据你的电脑硬件进行修改

![Static Badge](https://img.shields.io/badge/%E6%94%AF%E6%8C%81%E7%9A%84macOS%E7%89%88%E6%9C%AC-Catalina%2010.15%20~%20Sequoia%2015.1-block?logo=apple)  ![Static Badge](https://img.shields.io/badge/OpenCore%E7%89%88%E6%9C%AC-1.0.1-33163)


## 参考

[主页 - 国光的黑苹果安装教程：手把手教你配置 OpenCore (sqlsec.com)](https://apple.sqlsec.com/)

[mikigal/Ryzen-hackintosh(github.com)](https://github.com/mikigal/ryzen-hackintosh)

[JeoJay127/RapidEFI-Tool(github.com)](https://github.com/JeoJay127/RapidEFI-Tool)

[OpenCore安装指南 (sumingyd.github.io)](https://sumingyd.github.io/OpenCore-Install-Guide/)

## 硬件配置

- CPU：AMD Ryzen 3 4100（基准频率：3.80GHz，4核8线程）
- GPU：柏能/蓝宝石 AMD RX 460白金版（4GB显存）
- 主板：铭瑄 MS-挑战者 A320M.2-VH
- 内存：镁光 DDR4 3200MHz 16GB
- 网卡：Realtek RTL8111（1Gbps）
- 声卡：Realtek ALC662
- 硬盘：七彩虹 CN600 M.2 512GB（PCle3.0）


## 完美程度

> [!NOTE]
>
> ”已勾上“代表该项功能可正常使用；“未勾上”代表该项功能无法实现

> [!IMPORTANT]
>
> 一部分功能没有实现是因为由于需要外置PCle无线网卡去驱动，但恰巧手里没有任何可用的闲置网卡供折腾。如果你有PCle网卡，那就可以接近80%白苹果完整度



- [x] 睡眠唤醒
- [x] CPU睿频
- [x] 以太网
- [x] 声音输出/麦克风
- [x] CPU/GPU传感器
- [x] 显卡（Matel/VDA）
- [ ] 隔空投送
- [ ] 接力
- [ ] 随航
- [ ] 跨设备粘贴
- [ ] 通用控制
- [ ] iPhone镜像（macOS Sequoia独占的功能）

## 截图
![0513839E83CCDFE531B1523D34FE2DB7](https://github.com/user-attachments/assets/e2b3dfaf-ea2a-4cdd-9e3c-e933eda598b3)
![QQ20240921-025441](https://github.com/user-attachments/assets/f4882587-b3a0-4613-877e-1aa8edf2a41f)


