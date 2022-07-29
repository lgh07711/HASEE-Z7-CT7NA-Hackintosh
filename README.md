# HASEE-Z7-CT7NA-Hackintosh
处理器        英特尔 Core i7-9750H @ 2.60GHz 六核
主板        Notebook NH5x_7xRCx,RDx ( HM370 芯片组 )
内存        32 GB ( 英睿达 DDR4 2666MHz )
主硬盘        金士顿 RBUSNS8154P3512GJ ( 512 GB / 固态硬盘 )
显卡        Nvidia GeForce GTX 1660 Ti ( 6 GB / 蓝天(CLEVO) )
显示器        友达 AUO31EB (自己更换的4K屏幕)
声卡        REALTEK  ALC293
网卡        英特尔 AX210


自用EFI-OC8.0
以上内容均来自互联网并自行组合。
如果你需要套用，请自行修改，安装前一定记得设置机型添加三码。


该配置文件为加快引导速度关闭了系统中对固态硬盘的Trim功能。如介意可修改Kernel>Quirks>SetApfsTrimTimeout值为-1。
本人机器自行更换了4K屏，机器为英特尔ax210无线网卡，MACOS12.4中现在蓝牙不能用，原装无线网卡的蓝牙应该正常。bios中已关闭CFG Lock。
本机自行定制了声卡。
