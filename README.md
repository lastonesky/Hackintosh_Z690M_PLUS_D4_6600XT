# Hackintosh_Z690M_PLUS_D4_6600XT
Support MacOS Version 12.5-13
Asus Z690M PLUS D4, 12600KF, RX6600XT

Configuration:

CPU: Intel I5 12600KF

MB:Asus Z690M PLUS D4 or Maxsun Terminator B660M

VGA: Asrock RX6600XT 8G

BT/WIFI:  Intel AX200

Wifi Driver need youself download from [https://github.com/OpenIntelWireless/itlwm/releases/tag/v2.1.0#]
itwlm can directly use, airportltlwm need add kext to config

What works:
Wifi,Audio,Ethernet,RX6600XT,Sleep,E-Core,BlueTooth

What doesn't works:

IGPU,RGB Controller,Thunderbolt

BIOS Version 2014

PS:If EFI is not first item In OpenCore Menu, Please select lastest item "Reset System", Reboot, then Select Mac(or Mac Installation)

Maxsun_B660 Folder contains a USB Mapping Kext File,If Using Maxsun Terminator B660M，Can use this file to overwrite EFI\Kext\UTBMap.kext

Chinese:

Monterey或者Ventura需要选择对应版本的WIFI驱动，否则会不稳定、重启等。建议禁用无线驱动，使用有线网络。
同时支持华硕Z690M PLUS D4主板和 铭瑄 终结者 B660M主板。但是铭瑄主板需要复制一下Maxsun_B660文件夹里的文件到EFI\Kext文件夹里（USB接口定制）。
BIOS的CFG_Lock不解锁就可以，解锁也没什么影响。已经在config.plist中启用了cfg_lock相关的配置。

注意：如果使用华硕主板，在看到启动菜单时，需要注意一下第一个启动项名称是否为EFI，如果不是，直接选择后面的Reset System重启电脑，否则进不去MacOS，会一直黑屏。铭瑄B660M没有这个问题

Credits:
  OpenCorePkg
  AppleALC
  VirtualSMC
  Lilu
  OpenIntelWireless
  and 
  
