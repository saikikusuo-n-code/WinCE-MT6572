# Windows Embedded Compact 7 BSP for MT6572

# ⚠️ Some parts of the code might be AI assisted or generated; if you do not like this, consider looking for a similar project somewhere else :) ⚠️ 

## IMPORTANT!

This BSP is partily based off of the TMDSEVM3530 BSP from Texas Instruments and MTK kernel sources.

## Testing notes:

Testing device used is Sagereal GM2806 (sold under different brands and various configurations).

### Specifications 

| Component     | Model         | Information   |
| ------------- | ------------- | ------------- |
| SoC | MediaTek MT6572 | ARMv7 dual core at 1.2GHz, features various IO for display, cellular, sound etc. |
| Graphics | Mali 400MP | None |
| Display | CM-280A75-B-0x | 16-bit 8080 ST7789V 2.8" |
| Storage | ESMT FM6BD4G2GXB | 512MB NAND + 256MB LPDDR2 |
| I/O | microUSB | None |
| Camera | Unknown | Uses a GC2145 sensor | 

## Current states:

| Component     | State         | Information   |
| ------------- | ------------- | ------------- |
| Bootloader | ❌ | Not started yet |
| Storage | ❌ | Not started yet; the testing device used uses NAND; if you have an EMMC phone, contribute here |
| Display | ❌ | Not started yet; the testing device used uses parallel display; if you have one with MIPI, contribute here |
| Inputs | ❌ | Not started yet; the testing device is keypad-driven; if yours has touchscreen, contribute here |
| Graphics | ❌ | Not started yet |
| Power | ❌ | Not started yet |
| Sound | ❌ | Not started yet |
