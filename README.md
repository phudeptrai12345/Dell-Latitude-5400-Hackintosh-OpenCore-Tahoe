# Dell-Latitude-5400-Hackintosh-OpenCore-Tahoe
OpenCore EFI to run MacOS on Dell Latitude 5400

Hackintosh for Dell Latitude 5400
| | |
|-|-|
|**CPU**|Intel Core i5-8365U CPU|
|**RAM**|8GB DDR4 2666MHz|
|**IGPU**|Intel UHD 620|
|**SSD**|BC511 NVMe SK hynix 256GB|
|**ETH**|Intel I217-LM|
|**WLAN+BT**|Intel 9560NGW |
|**Audio**|Realtek ALC236|
|**Ports**|USB-C (PD+DP-AltMode), 3xUSB3.0, HDMI, microSD, Multi-Jack, DC|



<img width="416" height="637" alt="Ảnh màn hình 2025-10-05 lúc 15 13 30" src="https://github.com/user-attachments/assets/ae34cfa1-a734-4056-bb89-9e4c8a8151d0" />

Fix for audio :
step 1 : run VoodooHDA-Tahoe.pkg and follow its instructions.
step2 : please follow the picture:
![fix adiou1](https://github.com/user-attachments/assets/f25645dd-259e-4406-9aac-ef7d88ba46b0)
![2fix adiou](https://github.com/user-attachments/assets/43ad71a6-bb3c-4dc2-8d8c-7466a469aeb0)

To fix wifi 
run HeliPort.dmg

Working

    Everything what is not in the Not working section :D
    Bluetooth (4.0, LE, Handoff) [out-of-the-box, no kext needed]
    WLAN [no kext needed] (recommended)
    Intel WLAN [kexts added, but not that stable]
    Ethernet
    HDMI, DisplayPort Alt Mode (all with sound, but no volume adjustment)
    USB-C (I'm using it with a docking station all the time)
    USB ports mapped, working after sleep
    TrackPad with gestures (visible as Magic Trackpad 2)
    Audio, with speaker and microphone support
    QE/CI
    Sleep
    TouchPad buttons
    TrackStick
    Multi-Jack (both cold- and hotplug)
    Dedicated brightness control keys 


⚠️ WARNING ⚠️
It's just a guide and the efi is from my device so it may not be compatible with your device.
Some AML files and other EFI files **may not work on your machine**.  
You need to **check, tweak, and test** before booting.  

Backup your EFI first!  
USE AT YOUR OWN RISK.
## Contributors

- phudeptrai12345 [phudeptrai12345](https://github.com/phudeptrai12345)

