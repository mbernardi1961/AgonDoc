# Hardware known to work with ArgonLight and its variants

[Compatible Keyboards](https://docs.google.com/spreadsheets/d/1-6_sz6l-vJW5rFg3M0Y6bwC0hmFS7U6PPNjIZ9plrM8/edit#gid=0).
This Google Doc file contains known working keyboards (it is of course incomplete).

The UEXT (Universal-EXTension-Connector) connection was developed by [OLiMEX](https://www.olimex.com/Products/Modules/) as a board to board connector which supports three serial communication interfaces - I2C, SPI and RS232. It is a great way to expand the features of the AgonLight2. While all modules should be available from OLiMEX, many will also be available from [your local distributor](https://www.olimex.com/Distributors/).

[AgonLight2-HvIO](https://olimex.wordpress.com/2023/06/26/agonlight2-hvio-is-open-source-hardware-board-which-adds-4-ssr-outputs-and-4-optoisolated-inputs-to-agonlight2-retro-z80-computer/) allows you to switch on and off High Voltage Loads like Lamps etc with up to 1A current. It also has 4 opto isolated inputs which detects 110/220VAC.

[AgonLight2-Proto](https://www.olimex.com/Products/Retro-Computers/AgonLight2-Proto/open-source-hardware) is a small board with dimensions 100x80mm. It allows you to fast prototype hardware concepts and ideas for AgonLight2 computer.

[UEXT Port Splitter and Extender](https://www.olimex.com/Products/Modules/Adapters/UEXTx5/open-source-hardware) with 5 UEXT Connectors wired in parallel. Allowing multiple modules to be connected at the same time.

[MOD-WIFI-ESP8266](https://www.olimex.com/Products/IoT/ESP8266/MOD-WIFI-ESP8266/open-source-hardware) is a UEXT expansion module with a ESP8266 UART to WIFI IC. With this module you can add WIFI capablities to the AgonLight2. 

[MOD-RS232](https://www.olimex.com/Products/Modules/Interface/MOD-RS232/open-source-hardware) is an RS232 level-shifter with UEXT connector. Using this module you can connect an AgonLight2 to an RS232 device.

[Console8 compatible joystick interface for AgonLight2](https://www.pcbway.com/project/shareproject/Agon_ARCADE_Joystick_Interface_893b9d84.html) available from PCBWay.

[Prototype joystick and mouse interface for AgonLight2](https://github.com/BlastBrothers/agon-mega-io) currently in a breadboard state.

# Documentation related to the above hardware

Software to allow use of the MOD-WiFi module can be found on [GitHub](
https://github.com/nihirash/Agon-MOS-Tools/tree/main/esp8266).
<!-- Addition documentation for neo6502 - 
https://www.makerhacks.com/neo6502-serial-wifi/ -->
Documentation on how to use the  AgonLight2-Proto board can be found on [GitHub](https://github.com/OLIMEX/AgonLight2-Proto).

Documentation on how to use the 
AgonLight2 High Voltage Interface board can be found on [GitHub](https://github.com/OLIMEX/AgonLight2-HvIO).
