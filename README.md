# Lenovo-E49-Bigsur--EFI

 Lenovo-E49-BigSur-EFI-with-OC0.6.2
 
 系统是Bigsur 11.2 黑果小兵上的Bigsur 11.2
 
 截图：
 ![总览](https://user-images.githubusercontent.com/95116110/167303238-ef21def1-3f5f-45c7-ad5c-7f13b780d258.png)

设备及功能正常：网卡、无线、触控板、摄像头、读卡器、CPU睿频、合盖睡眠、唤醒、亮度调整、音量调整

### 我的配置：
| CPU | i5-3320M |
| ---- | ---- |
| RAM | DDR3L 1600MHz 4G |
| 存储 | 128G SSD |
| 网卡 | Intel N2230 |  

PS：网卡本来就在BIOS的白名单里，不用刷BIOS

### BIOS选项

Config:
| 选项 | 状态 |
| ---- | ---- |
|Network --> Wake On LAN | Disabled |
|Display --> NVIDIA Optimus | Disabled |
|Serial ATA --> SATA Controller Mode Option | AHCI |
| CPU | All Enabled (全部为Enabled) |

Security:
| 选项 | 状态 |
| ---- | ---- |
| Virtualization | All Enabled (全部为Enabled) |
| Secure Boot | Disabled |


| I/O Port Access | 状态 |
| ---- | ---- |
| Bluetooth | Disabled |
| eSATA Port | Disabled |
| Fingerprint Reader | Disabled |

| Anti-Theft | 状态 |
| ---- | ---- |
| Current Setting | Disabled |
| Computrace --> Current Setting | Disabled |


### 系统概览：
网卡：
![WIFI](https://user-images.githubusercontent.com/95116110/167303262-f62e0d32-bc7f-4b8c-bfef-a4e72f20e50a.png)

电池：
![电池](https://user-images.githubusercontent.com/95116110/167303278-b9edec4e-3067-47fc-b7f6-2d8bfe7c0959.png)

**关于"Config.plist"配置请参照：**
https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/ivy-bridge.html

取回使用时别忘了改SMBIOS 

Windows端建议使用OCAT配置Config.plist文件
