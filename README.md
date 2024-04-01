# Hackintosh_Z690M_PLUS_D4_6600XT  

OpenCore Version: 0.9.9  
Support MacOS Version : BigSur, Monterey, Ventura, Sonoma  
Maxsun B660M Terninator, 12600KF, RX6600XT 

Configuration:  

CPU: Intel I5 12600KF  
MB:Asus Z690M PLUS D4 or Maxsun Terminator B660M  
VGA: Asrock RX6600XT 8G  
BT/WIFI:  Intel AX200  

What works: 
Wifi,Audio,Ethernet(RTL8125),RX6600XT,Sleep,BlueTooth 

PS:If EFI is not first item In OpenCore Menu, Please select lastest item "Reset System", Reboot, then Select Mac(or Mac Installation)  

This EFI file comes from [RapidEFI-tool](https://github.com/JeoJay127/RapidEFI-Tool), it can generate EFI automaticlly.


Chinese: 

这个文件来自于[RapidEFI-Tool](https://github.com/JeoJay127/RapidEFI-Tool)  
这个工具能自动生成所需的EFI，经测试已经可以很好的工作在铭瑄B660M终结者上，所以以后本仓库不再更新，请大家使用RapidEFI-Tool自行生成所需EFI。  
唯一需要注意的是，生成EFI时，声卡驱动那里ALC布局需要选择：11，使用AppleALC仿冒内建声卡。  
同时支持华硕Z690M PLUS D4主板和 铭瑄 终结者 B660M主板。  

注意：如果使用华硕主板，在看到启动菜单时，需要注意一下第一个启动项名称是否为EFI，如果不是，直接选择后面的Reset System重启电脑，否则进不去MacOS，会一直黑屏。铭瑄B660M没有这个问题  

Credits:  
  [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg)  
  [AppleALC](https://github.com/acidanthera/AppleALC)  
  [VirtualSMC](https://github.com/acidanthera/VirtualSMC)  
  [Lilu](https://github.com/acidanthera/Lilu)  
  
