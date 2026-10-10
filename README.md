# Vincent Besson

*In Dust I Trust.* Hardware and firmware for machines that were never supposed to still be running.

## Retro hardware

### SmartDisk II

A floppy drive emulator for the Apple II family that reproduces the timing of a real Disk II and
UniDisk 3.5, so copy-protected titles boot from an SD card exactly as they did from the original media.

| Repository | What it is |
|---|---|
| [AppleIIDiskIIStm32F411](https://github.com/vibr77/AppleIIDiskIIStm32F411) | The SmartDisk II itself: STM32F411 firmware, hardware and 3D-printed case. Releases on the right of the page. |
| [SmartPortAdapter](https://github.com/vibr77/SmartPortAdapter) | DB19 to IDC20 adapter to connect the SmartDisk II to an Apple IIc or IIGS. |
| [Smartloader](https://github.com/vibr77/Smartloader) | 6502 disk browser that runs on the Apple II: list the images on the SD card and boot one from the screen. Custom boot sectors and fast RWTS. |
| [bootloader](https://github.com/vibr77/AppleIIDiskIIStm32F411/tree/main/bootloader) | Custom UF2 bootloader for the STM32F411: drag-and-drop firmware updates over USB. Current firmware needs v0.14 or v0.16. |
