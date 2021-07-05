![alt text](https://github.com/thetechsir/acer-nitro-515-54-OPENCORE-Monterey/blob/main/banner-nitro-opencoreGITHUB.png)
# acer-nitro-515-54-OPENCORE-Monterey
acer nitro 515-54 monterey working OC 70

Acer Nitro 515-54-55YM
OpenCore .70 Monterey 

~~All Working~~
Intel UHD Graphics 630 (Mobile) - full metal support
USB C, 3.1 and 2 ports
BCM4360 Wifi Bluetooth // Airdrop handoff sidecar working
Ethernet RTL811 working
Touchpad and keyboard fully working with ssdt’s
Battery fully recognized and display brightness works within os control
Boot windows through OpenCore or refind. 

Mac OS on sing sata SSD
Windows on 2 Raid 0 m.2 NVME drives with intel RST ON in bios. 
Opencore works with bios set to SATA OR Intel RST (sata unsupported kext)
Boot chime works usually lol

~~Not Working~~
NVIDIA GTX 1050 (disables with -wegnoegpu)
	will only with with high Sierra.. no thanks
	ill live without the cdmi port while in osx, battery on battery anyway!

CPU:Intel i5 9300h 4c8t

GPU: ogpu intel UHD 630 / Nvidia gtx 1050

Wifi BT Replaced: BCM4360  

Use macserial to generate serials for MacBook Pro15,3
Select config and dump it in and you’re good to go!

Quick tip, if you wish to change your data or raid setup in bios, go to the second from right tab, and click ctrl + s and hidden menu will open so you can change it. Unless its set to data you won’t see your drives in linux or Mac unless you use kext data unsupported. I have it in this efi so shunt matter. 

Also, I’ve removed my serials so all you need to do is generate new ones and put them in. Also change for your hardware. But enjoy!
