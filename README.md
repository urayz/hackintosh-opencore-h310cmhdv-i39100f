# Hackintosh Big Sur H310CM-HDV i3-9100f (OpenCore)

## Specifications

| Name | Detail |
|--|--|
| Mac OS Version | Mac OS 11.1 Big Sur |
| OpenCore Version | v0.6.5|
| SMBIOS | iMacPro1,1|
| Motherboard | ASRock H310CM-HDV |
| Processor | Intel i3-9100f |
| Memory | VGEN Tsunami 2666Mhz 2x4GB (2400Mhz,CPU Limit) |
| Graphic Card | Nitro Sapphire+ RX 580 4GB |
| Audio Codec | Realtek ALC887 |
| Ethernet | Realtek RTL8111H |
| Monitor | Philips 200V4 1600x900 (VGA to HDMI) |
| Storage | Adata SU800 256GB |
| Others | TP-LINK UB400 Bluetooth Dongle |

## Status
![System Snapshot](https://user-images.githubusercontent.com/3191760/105627253-5b853b80-5e68-11eb-8dee-81bebec6b466.png)

**Working**

 - Ethernet :white_check_mark:
 - Power Management :white_check_mark:
 - Audio On Board :white_check_mark:
 - RX 580 Flawless :white_check_mark:
 - Sleep :white_check_mark:
 - USB ports were not mapped manually (not necessary).
 - HDMI and HDMI Audio work Out of The Box (of course RX 580 HDMI).
 - Bluetooth Dongle works Out of The Box w/o drivers.
 - Transition Animation is Smooth

**Questioning**

 - I think the GPU Sensor is not very accurate.
 - iMessage and Facetime has not been tested

**Not Working**

 - I dunno

 ## Short Brief
 At first I used Clover to install Big Sur, but after finished install process, the system got kernel panic loop and couldn't finish the installation. I managed to install it with Clover on Catalina and then update manually to Big Sur, but there were many things didn't work properly (couldn't log in to iCloud, Safari broken, Ethernet not work, Audio not work, dll).
 
 Clover quite a mess to start than OpenCore. With OpenCore the config file much cleaner, it's just use the necessary tweaks. The documentation was very helpful and detail. I managed to install Big Sur properly with guide from Dortania (https://dortania.github.io/OpenCore-Install-Guide/extras/big-sur/)

Just follows the guide from start to post install and everything will work as expected.
