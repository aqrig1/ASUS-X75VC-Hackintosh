# ASUS-X75VC-Hackintosh

![Screenshot](https://github.com/Jesterjke/ASUS-X75VC-Hackintosh/raw/master/Screenshots/Screen%20Shot%202019-05-06%20at%203.52.48%20PM.png)

## Notes
Clover config & kexts for macOS Mojave 10.14.3.
Please generate some other rom number for SMBIOS if you are gonna use this config. Check [this](www.tonymacx86.com/threads/an-idiots-guide-to-imessage.196827/) for more details.
Since this laptop is hardware-wise similar (except display size) to Asus X550VC & Asus X550CC it might work there too -
 you would need to disable HDMI patch & possibly play around with platform-id.

## Hardware
* Model: ASUS X75VC-TY056D
* CPU: Intel(R) Core(TM) i5-3230M CPU @ 2.60GHz
* Storage: SSD INTEL SSDSC2KW256G8 256GB + HDD TOSHIBA MQ01ABD075
* Video: Intel HD Graphics 4000
* Audio: Realtek ALC269
* LAN: Qualcomm Atheros, AR8161 Gigabit Ethernet
* Wifi: Originally some unsupported Realtek, replaced with Qualcomm Atheros, AR9285 Wireless Network Adapter (PCI-Express)

## BIOS
* Advanced - USB Configuration - XHCI Pre-Boot Mode {Enabled}  
* Advanced - USB Configuration - Legacy USB Support {Enabled}  
* Boot - Launch CSM {Disabled}  
* Boot - Launch PXE OpRom {Disabled}  
* Security - Secure Boot Control {Disabled}

## What's working
* Hardware accelerated graphics
* CPU power management
* Wi-Fi
* HDMI (video & audio)
* Brightness control
* Sound
* Touchpad (+gestures)
* USB Ports
* Ethernet
* Battery percentage (can't confirm that's working correctly since my battery is dead)
* Sleep & Wake
* Microphone
* FN buttons
* 3.5mm jack
* iCloud, iMessage

## Bugs/not working
* Camera (have not intention to look up for a fix)
* Brightness lowest level is higher that I had on Linux (lazily looking for a fix)

## Haven't tested
* VGA
* Some FN keys (sound & brightness control works though)
* hibernatemode anything other than 0
* Mic via combined jack
* USB 3

## References
* https://tonymacx86.com/threads/an-idiots-guide-to-imessage.196827/
* https://applelife.ru/threads/asus-x550vc-i-asus-x550cc.41752/
* http://mykubik.blogspot.com/2015/06/hackintosh.html

