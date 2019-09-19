KZ80 Designs
============

This is the actual KZ80 hardware.

+ backplane: KZ80 interconnect to 5-slot RC2014 bus.
+ mainboard: the current mainboard has 2x CY62256 32K RAM modules and an
  AT28C256 ROM. The ROM is attached to the lower 8K of the address space.
  This design does not feature paging out of the ROM, and as such is
  unsuitable for CP/M.
+ power: the power board provides the clock, a clock+5V connection to
  the mainboard, and a 3.3/5V connection to the I/O board.
