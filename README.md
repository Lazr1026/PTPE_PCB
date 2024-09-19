# PTPE_PCB
PCB for the Pico ToyPad Emulator

![](https://github.com/Lazr1026/PTPE_PCB/blob/main/pics/top.png?raw=true)
![](https://github.com/Lazr1026/PTPE_PCB/blob/main/pics/bottom.png?raw=true)

## BOM
- Pico (duh).
- [This screen](https://www.amazon.com/Display-Module-ST7735-128x160-STM32/dp/B07BFV69DZ). You can probably find something similar somewhere else for cheaper, but thats what I bought.
- [These tactile switches](https://www.amazon.com/1825910-6-Switch-Tactile-SPST-NO-0-05A/dp/B0CGYQHS7K) (the buttons). You can find cheaper probably on AliExpress, just search for "1825910-6". Make sure you get 5!

## Ordering Instructions
- Download and upload the `.zip` from the releases to JLCPCB / PCBWAY / OSHPark / etc.
- PCB does not need any specific option set, recommended to leave at defaults. You can do ENIG if you want, but that will jump the price way up.

## Assembly instructions
NOTE: Buttons and Screen can be done in any order you want, however the Pico MUST be done first.
- Start with soldering on the Pico. The screen will get in the way and the buttons *might*.
- Solder the buttons. (Or you can skip this and just use tweezers)
- Solder wires to the SD card pads (I recommend magnet wire for this), and then solder on the screen.
- Solder the SD card wires to the SD card pins on the screen.
