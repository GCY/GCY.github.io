---
title: "JLINK-ARM-OB"
excerpt: "DIY ARM ICE, JTAG, SWD. <br/> <img src='/res/JLINK-ARM-OB/mem%200x8000000%2040960/connect%20JLink-OB%20to%20STM32F405.png'  width='500' height='500'>"
collection: portfolio
---

<p align='center'>
<a href="https://github.com/GCY/JLINK-ARM-OB">Github</a>
</p>

This is JLink-OB ARM ICE tool, [STM32F103 Jan 7 2019 firmware](/res/JLINK-ARM-OB/JLink-OB%20STM32F103%20JLinkARM.dll%20v6.44f%20.bin) extract from v6.44 JLinkARM.dll.

This version([STM32F103 Jan 7 2019](/res/JLINK-ARM-OB/JLink-OB%20STM32F103%20JLinkARM.dll%20v6.44f%20.bin) ) failed to upgrade the firmware of the JLink-OB with JLinkConfig.

![](/res/JLINK-ARM-OB/JLinkARM.dll%20dump%20%20firmware.png)

## Use
 - 1.burning [STM32F103 Jan 7 2019 firmware](/res/JLINK-ARM-OB/JLink-OB%20STM32F103%20JLinkARM.dll%20v6.44f%20.bin) to DIY JLink-OB.
 - 2.Connect targer(For example the following picture is my [STM32F405 Digital Stethoscope project](https://github.com/GCY/Digital-Stethoscope-for-Heart-and-Lung-sounds))
![](/res/JLINK-ARM-OB/mem%200x8000000%2040960/jtag%20swd%20connect.png)

 - 1.Run JLinkExe.
 - 2.J-Link > connect.
 - 3.Select device.     # the example is STM32F405
 - 4.Device > S.        # for SWD Port
 - 5.Speed = 4000kHz
![](/res/JLINK-ARM-OB/mem%200x8000000%2040960/connect%20JLink-OB%20to%20STM32F405.png)

 - 1.J-Link > mem 0x8000000 40960
 - 2.Test dump target flash.
 - 3.You DIY JLink-OB done.
![](/res/JLINK-ARM-OB/mem%200x8000000%2040960/dump%20STM32F405%20mem%200x8000000%2040960%20with%20JLink-OB%201.png)

## Reference
 - [DIY JLink-OB-072 (JLink + COM)](http://akb77.com/g/stm32/jlink-ob/)
 - [JLink hack reference (cht)](https://www.amobbs.com/thread-5653964-1-1.html)
 - [J-Link Commander](https://wiki.segger.com/J-Link_Commander#savebin)
 - [Firmware extract from JLinkARM.dll (cht)](https://blog.csdn.net/qq_39663845/article/details/81086499)
