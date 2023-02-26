# m5n88Q
PC-8801 emulator[QUASI88] for M5Stack Core2 

This is a fork to support M5Stack Core2 with M5Unified from [the original](https://github.com/shikarunochi/m5n88Q) only for M5Stack FIRE.

## How to build and upload
Prepare platformio environment, and
```
 $ git clone https://github.com/nyasu3w/m5n88Q.git
 $ cd m5n88Q/m5n88Q
 $ pio run --target=upload
```
or you can use VisualStudioCode PlatformIO extension.

## How to run
- SD card is necessary to store ROM images, DISK images and so on
- Store the ROM images in /PC88ROM/ in SD
- Store the DISK images in /PC88ROM/DISK/ in SD
- Press BtnB to select disk menu. Press BtnC to system menu.

Enjoy!

## Note
- NO SOUND supported
- SLOW
- LovyanLauncher is not supported for now.
- Combined PC88SR format ROM image is supported if it is located at /PC88ROM/PC88.ROM
- The finding ROM image names are output to the serial console
- Needs PSRAM, so it will not run on M5Stack Basic and so on.
- You might change the board setting in platformio.ini

---

The original readme is following.

---

PC-8801 emulator[QUASI88] for M5Stack FIRE

http://shikarunochi.matrix.jp/?p=2964
