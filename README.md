# RyzeTelloFirmware
```Firmware images for hacking, reverse engineering, and teardown of the Ryze / DJI / Intel Movidius Tello
Images are pulled from 52.84.27.109 /paraconfig_file and /firmware_file (DJI process)

Tello is Powered by a DJIGlobal flight control system and an Intel processor
```
https://www.ryzerobotics.com/tello
```
Tello is based on Intel Movidius MA2x chipset
```
https://www.youtube.com/watch?v=hX0UELNRR1I
```
Hello Tello - Ryze Announces Intel Myriad VPU Powered Toy Drone
```
https://www.movidius.com/news/hello-tello-ryze-announces-intel-myriad-vpu-powered-toy-drone
```
MA2x is based on a SARC LEON processor
```
https://en.wikipedia.org/wiki/LEON
```
Myriad 2 programming paradigms
```
http://eyesofthings.eu/wp-content/uploads/deliverables/EoT_D3.3.pdf
```
MYriad 2: Eye of the Computational Vision Storm
```
https://www.hotchips.org/wp-content/uploads/hc_archives/hc26/HC26-12-day2-epub/HC26.12-6-HP-ASICs-epub/HC26.12.620-Myriad2-Eye-Moloney-Movidius-provided.pdf
```
Myriad 2: Application Processor Description
```
http://eyesofthings.eu/wp-content/uploads/deliverables/EoT_D2.3.pdf
```
Random relevant resources for Reverse Engineering:
```
https://tellopilots.com/threads/tello-whats-possible.88/page-4#post-1172
https://zhuanlan.zhihu.com/p/33911052
```
Tello SPI flash (GigaDevice GD25Q64C) can be dumped with GoodFET:
```
http://goodfet.sourceforge.net/clients/goodfetspiflash/
https://www.scribd.com/document/362117009/GigaDevice-GD25Q64C-SPI-Flash-Datasheet
```
Also on the PCB is a TI bq24259
```
http://www.ti.com/lit/ds/symlink/bq24259.pdf
```
WiFi Soc is Marvell Avastar 88W8801
```
http://www.marvell.com/microcontrollers/wi-fi-microcontroller-platform/home-kit/index.jsp
```
PMU by Active Semi ACT8846
```
https://active-semi.com/wp-content/uploads/ACT8846_Datasheet.pdf
```
Tell can be programmed via Scratch, or via "Tello SDK" commands (via the provided python for example)
```
https://dl-cdn.ryzerobotics.com/downloads/tello/0228/Tello+SDK+Readme.pdf
https://dl-cdn.ryzerobotics.com/downloads/tello/20180222/Tello3.py
```
Scratch detail:
```
https://dl-cdn.ryzerobotics.com/downloads/tello/0222/Tello+Scratch+Readme.pdf
https://dl-cdn.ryzerobotics.com/downloads/tello/20180222/Scratch.zip

