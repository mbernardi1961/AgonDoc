# How to update AgonLight Firmware

<b>For new owners of the AgonLight2 who wish to upgrade the Quark Firmware on their newly purchased device</b>.

The AgonLight microcomputer was designed to allow its firmware to be upgraded, but initially it required special hardware to do so.
In January 2023 a software solution was developed which can be found at https://github.com/envenomator/agon-flash/.
The latest version allows MOS version 1.03 and VDP 1.04 to be updated without any additional hardware.

To update MOS 1.03 to 1.04 or later install the agon-flash utility from the github repository above. Always flash the Quark MOS before upgrading the VDP.

To update VDP 1.03 to 1.04 is slightly more complicated. First you need a USB-A to USB-C data cable (to connect your computer to your AgonLight2). You may also need to change a jumper setting on the board to allow writing to the ESP32. It is then necessary to find out which COM Port the Agon appears as on your PC. [In Windows look in Device Manager, Ports. (If there isn't a Port entry the usb cable may not be rated for data.)] You then need to copy the files in https://github.com/envenomator/agon-binaries/tree/master/VDP/Quark%201.04/ into a folder on your PC. Once this is done; run the flash script as "flash COM3" where the COM3 will change depinding on the pc configuration. If all is correct the firmware will be copied to the AgonLight2 and after a reboot the VDP should be updated to version 1.04
Once at version 1.04 then both the MOS and VDP can be updated using the agon-flash utility installed on the Agon SD card.

If your Agon has an earlier version of the Quark Firmware installed use the instruction at https://github.com/breakintoprogram/agon-docs/wiki/Updating-Firmware

Note this may work with other Agon versions, but I have only tested it on the AgonLight2.

Once you have the Quark Firmware version 1.04 installed you can use the [flash software](https://github.com/envenomator/agon-flash/) to update to newer versions. This includes the version for the [Console 8](https://github.com/AgonConsole8).
<!-- Quark Firmware can be found as {MOS}(mos.bin) and {VDP}(firmware.bin) -->
