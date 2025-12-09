# Atari ST cable for the 6-pin analog input

This cabling can be used to plug an Atari ST running in monochrome
mode into the Analog RGBtoHDMI.

## Wiring the video

| RGBtoHDMI 6 way IDC | 13 way DIN  | Notes
| ------------------- | ----------- | ---------------------------
| Pin 1 GND           | Pin 13 & 4  | pin 4 is mono mode switch
| Pin 2 SYNC          | Pin 9       | HSYNC
| Pin 3 BLUE          | Pin 11      | Video signal
| Pin 4 GREEN         | Pin 12      | VSYNC
| Pin 5 RED           | n.c.        |
| Pin 6 +5V           | n.c.        |

## Wring audio (optional)

When you need to also access the analog audio that comes from the A/V connector,
you can take the mono audio signal from pin 1 of the 13 way connector.

## RGBtoHDMI profile

Because setting up the profile is a tricky business, I will provide this here, in case
the RGBtoHDMI does not support this out of the box. 
After installing the latest beta release of the RGBtoHDMI software, you need to 
add the files from 
[this archive](atari_st_extrafiles.zip)
to the installation.
