
# ELEC3730 - STM32H747I-DISCO

A base setup for the STM32H747I-DISCO Discovery board for ELEC3730.

It has been setup as follows:
- Pins cleared.
- Clock reconfigured.
- Removal of boot code within the CM7 core - CM4 not used.
- Semihosting enabled.
- User LEDS configured as LEDRed, LEDBlue, etc.
- TIMER 2 setup, PSC: 20000, Period: 9001
- TIMER 2 Callback
- Interrupts enabled EXT line 15:10.
- Interrupt enabled for Blue Wakeup Button (PC13) - Rising edge - with callback function.


