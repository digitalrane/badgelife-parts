LSAO Parts
==========

Various resources for building PCBs with SAO and LSAO ports for building badges or badge addons.
The LSAO connector is an iteration on the DEFCON SAO port which adds UART (or 2x GPIO), SPI, and the RST signal if implemented, to help with badge programming.
The physical connector is a 2x5 2.54" pin header on a badge, and socket on the add-on. Ideally, the pins should not be pre-soldered, this should be an exercise left to the delegate.

Current Resources
-----------------

`LSAO.lib` - KiCad schematic footprint for LSAO. Includes SAO.
Use either the "Connector_PinSocket_2.54mm:PinSocket_2x05_P2.54mm_Vertical" (for addons) or "Connector_PinHeader_2.54mm:PinHeader_2x05_P2.54mm_Vertical" (for badged) PCB footprint.
A custom PCB footprint could be produced to add pin definitions to the silkscreen. Pull requests accepted!
