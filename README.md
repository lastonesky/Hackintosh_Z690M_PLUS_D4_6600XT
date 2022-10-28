# Hackintosh_Z690M_PLUS_D4_6600XT

Asus Z690M PLUS D4, 12600KF, RX6600XT

Configuration:

CPU: Intel I5 12600KF

MB:Asus Z690M PLUS D4

VGA: Asrock RX6600XT 8G

BT/WIFI:  Intel AX200

Wifi Driver need youself download from [https://github.com/OpenIntelWireless/itlwm/releases/tag/v2.1.0#]
itwlm can directly use, airportltlwm need add kext to config

What works:
Wifi,Audio,Ethernet,RX6600XT,Sleep,E-Core,BlueTooth

What doesn't works:

IGPU,RGB Controller,Thunderbolt

BIOS Version 2014
to unlock CFG_Lock,in oc menu ,choose mod Grub Shell,then input following text(only in Version 2014 BIOS):
setup_var_cv CpuSetup 0x44 0x01 0x00

PS:If EFI is not first item In OpenCore Menu, Please select lastest item "Reset System", Reboot, then Select Mac(or Mac Installation)

