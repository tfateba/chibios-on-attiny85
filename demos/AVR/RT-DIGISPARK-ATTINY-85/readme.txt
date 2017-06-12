*****************************************************************************
** ChibiOS/RT port for Atmel AVR ATTiny85.                                 **
*****************************************************************************

** TARGET **

The demo runs on a Digispark Kickstarter board based on an ATtiny85.

** The Demo **

The demo currently just toggles the test/status LED every second.
The LED is connected to the PB1 pin of the ATtiny85 MCU. This pin corresponds
to P0 on the Digispark board.

** Build Procedure **

The demo was built using the GCC AVR toolchain. It should build with WinAVR too!
Just run the command "make" to build this example.

** Notes **

The ATtiny85 is pre-programmed with a bootloader. Thus it can act as an USB
device.
The Digispark runs the “micronucleus tiny85” bootloader. This bootloader comes
with a command line tool which can be used to program the board.
Form more details, llok at the Makefile.
