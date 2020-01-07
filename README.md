# BlackMagicProbe-64k

The 64K only versions of BlackMagicProbe in order to fit in STM32F103C8T6 MCUs.

Download the source code from https://github.com/blacksphere/blackmagic/

Patch the source according to the supported JTAG target:

- git apply lpc-only.patch for lpc11xx, lpc15xx JTAG targets support
- git apply stm32f-only.patch for stm32f1 and stm32f4 JTAG targets support
