# Lenovo-E49-Bigsur--EFI

 Lenovo-E49-BigSur-EFI-with-OC0.6.2
 
 系统是Bigsur 11.2 黑果小兵上的Bigsur 11.2
 
 截图：
 ![总览](https://user-images.githubusercontent.com/95116110/167303238-ef21def1-3f5f-45c7-ad5c-7f13b780d258.png)

设备及功能正常：网卡、无线、触控板、摄像头、读卡器、CPU睿频、合盖睡眠、唤醒、亮度调整、音量调整

### 我的配置：
| ---- | ---- |
| CPU | i5-3320M |
| RAM | DDR3L 1600MHz 4G |
| 存储 | 128G SSD |
| 网卡 | Intel N2230 |  

### 开启前 vs 开启后 
 
|  | 开启前 | 开启后 |
| ---- | ---- | ---- |
|头像| [](./doc/avatar2.png) |![](./doc/avatar1.png)  |
|clone |![](./doc/clone-before.png) |![](./doc/clone.png)    |  
|zip 下载 |![](./doc/download-before.png) |![](./doc/download.png)秒下的，实在截不到速度的图    |  


PS：网卡本来就在BIOS的白名单里，不用刷BIOS

网卡：
![WIFI](https://user-images.githubusercontent.com/95116110/167303262-f62e0d32-bc7f-4b8c-bfef-a4e72f20e50a.png)

电池：
![电池](https://user-images.githubusercontent.com/95116110/167303278-b9edec4e-3067-47fc-b7f6-2d8bfe7c0959.png)

**关于"Config.plist"配置请参照：**
https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/ivy-bridge.html

取回使用时别忘了改SMBIOS 

Windows端建议使用OCAT配置Config.plist文件
