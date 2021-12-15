#Ryzentosh // Hackintosh EFI (macOS High Sierra 10.13.6 (17G14042; initially 17G66)) for the setup :
CPU: AMD Ryzen 5 3500
GPU: NVIDIA GeForce GTX 970 4GB
Motherboard: ASUS EX-A320M-GAMING // Asus EX A320m Gaming (just leaving tags so people would find it easier from google)
Motherboard BIOS Version: 
Storage: 500GB NVMe (Windows installed) // 120GB SATA SSD (Used for macOS) // 500GB Seagate Barracuda HDD // 1TB Seagate HDD 
RAM: 16GB XPG ADATA 3200Mhz (8x2) (DOCP Enabled)


NOTES: 

-)  replace/remove 'nvda_drv_vrl=1' and 'shikigva=40' and instead use 'nv_disable=1' until you set up Web drivers, after         which you may add these 2 boot arguments and reboot macOS. 

-)  Kernel patch 32 'replace' value has been changed from default, refer to the following links:  
    https://i.imgur.com/GBJh2py.png  
    https://shorturl.at/qHIST
    Without this modification boot process gets halted at 'ioconsoleusers gioscreenlockstate 3...'
    If facing any issues change it back
    
-)  For audio, you may replace the Voodoo kext to AppleALC but this will break the mic inputs from 3.5mm jack. AppleALC will     give better and louder sound but it comes at the cost of breaking 3.5mm mic input. Also add alcid=1 in boot-args if using     AppleALC.

-) Install Nvidia Web Drivers from: https://github.com/Benjamin-Dobell/nvidia-update

-) Fix for Disocrd/CSGO/Adobe apps: https://github.com/Pavo-IM/amd_hackintosh_discord_fix

Screenshots: https://imgur.com/a/f6y2EOh

I'll leave a few links that helped me:
https://dortania.github.io/OpenCore-Install-Guide/
https://www.youtube.com/watch?v=XkxsbhRH77s
https://www.youtube.com/watch?v=RDQIO25HLHk


