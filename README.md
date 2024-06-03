This repository holds the design sources for a custom PCB and plate for the cycle 7 by TKD. I ordered a prototype and got that working but I do not guarantee anything.

***Note that I used a 12 MHz oscillator instead of an 8 MHz which would be QMKs default frequency for the STM32F401. That is no problem, but requires a little extra configuration. If you don't fancy that, change the oscillator circuit to 8 MHz.***

***Also the design replaces the standard 6.25u spacebar with a 1.25u key, a 2.75u key and a 2.25u key (in this order from the left). Very few keycap sets come with a 1.25 spacebar key, so you might want to change the design to use a different spacebar configuration. If you do that you also need to adjust the plate. If you plan to use the original plate of the cycle 7 you need to change the pcb design to a default 6.25u spacebar.***

Why make my own pcb for the cycle 7? Bootloader on TKD's PCB ~~is shit~~ does not comply with my requirements. Also the firmware is proprietary.

What about this PCB? Sources are here and free to use however you want. **However use at your own risk, I do not guarantee any of this to be functional**
The QMK configuration for the keyboard is available at [zegonix/zegonix-qmk/cycle7](https://github.com/zegonix/zegonix-qmk).
