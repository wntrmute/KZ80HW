KZ80 tooling
============

This contains support hardware, such as programmers.


+ aepro: AVR EEPROM Programmer
  + 27C512 version
  + 28C256 version
+ busmon: Z80 bus monitor
+ eeprom_adapter: 28-pin wide DIL to ZIF adapter
  + adapter27: for 27C512
  + adapter28: for 28C256
+ m328pgm: ATmega328 programmer for use with AVRISP mkII
+ m1284pgm: ATmega1284 programmer for use with AVRISP mkII
+ RC2014_SIO2: RC2014-compatible SIO/2 board
  + This is built from the standard enhanced-bus SIO/2 board,
    but it only uses the standard (39-pin) RC2014 bus.
  + Note: clock speed is derived from the RC2014 bus, and must
    be 7.4 MHz for 115200 baud operation.
+ SIO2_dev: RC2014 SIO/2 converted to KZ80 interconnect.
+ sercon: standalone serial console

All designs except SIO2_dev are on order but are, as of yet, untested.
