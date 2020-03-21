# ASUSu310uq-efi
黑苹果 hackintosh 华硕ASUS u310uq 10.13.6（i5 6200U/8GB/256GB）

一、机型配置
硬件	型号
处理器名称	Intel 酷睿i5 6200U
主板名称	华硕ASUS u310uq（i5 6200U/8GB/256GB）
系统内存	8192MB (DDR3 SDRAM 1866mhz)
显示适配器	Intel(R) HD Graphics 520 (2 GB)
显示器	[13.3" LCD]1080P
音频适配器	Conexant SmartAudio HD（14f1-1f72）
WiFi 蓝牙	bcm94360cs2 自行更换，无白名单

二、安装之前BIOS设置
-bios中将raid硬盘模式切换为ahci
-Disabled Secure Boot  
-uefi only →legancy support
三、运行状态
正常运行列表
显卡HD520驱动正常，注入ID 0x19160000  
声卡驱动正常，注入ID 13   
usb正常，usbinjectall.kext+ssdt_uiac.aml定制  
HDMI输出正常  
睡眠唤醒正常  
原生电源管理  
亮度调节  
wifi蓝牙正常  
iMessage、FaceTime、iCloud、airdrop正常  
系统可随意升级，注意更新clover版本跟驱动版本  
不正常运行列表
sd读卡器  
