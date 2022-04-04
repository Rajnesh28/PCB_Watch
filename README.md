# PCB Watch


## Features

- Uses RTC with a 32.768kHz external crystal oscillator to get accurate time, and square wave output
- 16x2 LCD display, with a I2C to QSPI adapter module
- ATMega88 controls these two peripherals on an I2C bus, gets time from RTC, and provides it to the display.
- Programmed with external ISP connection

For your own knowledge, I provide a detailed explanation of 
- Schematic and PCB
- Design Choices
- Calculations

And more so you can make your own electronic watch, and hopefully improve on the design.
