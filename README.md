# Newbie FAQ for AgonLight2 - How to update Firmware

<bold>For new owners of the AgonLight2 who wish to upgrade the Quark Firmware on their newly purchased device</bold>.<br>
The Argon microcomputer was designed to allow its firmware to be upgraded, but initially it required special hardware to do so.
In January 2023 a software solution was developed which can be found at https://github.com/envenomator/agon-flash/.
The latest version allows MOS version 1.03 and VDP 1.04 to be updated without any additional hardware.

To update MOS 1.03 to 1.04 or later install the agon-lash utility from the github repository above. Always flash the Quark MOS before upgrading the VDP.

To update VDP 1.03 to 1.04 is slightly more comlicated. First you need a USB-A to USB-C data cable (to connect your computer to your AgonLight2). You may also need to change a jumper setting on the board to allow writing to the ESP32. It is then necessary to find out which COM Port the Agon appears as on your PC. (In Windows look in Device Manager, Ports. (If there isn't a Port entry the usb cable may not be rated for data.) You then need to copy the files in https://github.com/envenomator/agon-binaries/tree/master/VDP/Quark%201.04/ into a folder on your PC. Once this is done; run the flash script as "flash COM3" where the COM3 will change depinding on the pc configuration. If all is correct the firmware will be copied to the AgonLight2 and after a reboot the VDP should be update to version 1.04
Once at version 1.04 then both the MOS and VDP can be updated using the agon-flash utility installed on the Agon SD card.

If your Agon has an earlier version of the Quark Firmware installed use the instruction at https://github.com/breakintoprogram/agon-docs/wiki/Updating-Firmware

Note this may work with other Agon versions, but I have only tested it on the AgonLight2.

# Other useful Agon repositories
Dean Belfield working on the official Quark firmware for the Agon Light microcomputer board - https://github.com/breakintoprogram

A batteries-included SDCard template for Agon Light / Agon Light 2 / Console8 - https://github.com/tomm/popup-mos

Agon Console8 from heber.co.uk - https://github.com/AgonConsole8

Official Agon Light Wiki - https://github.com/breakintoprogram/agon-docs/wiki


