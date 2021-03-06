# PCB Watch


## Features

- Uses RTC with a 32.768kHz external crystal oscillator to get accurate time, and square wave output
- 16x2 LCD display, with a I2C to QSPI adapter module
- ATMega88 controls these two peripherals on an I2C bus, gets time from RTC, and provides it to the display.
- Programmed with external ISP connection

For your own knowledge, I will provide a detailed explanation of 
- Schematic and PCB
- Design Choices
- Calculations
- How to do Bare-Metal Programming

And more so you can make your own electronic watch, and hopefully improve on the design.

Current draft schematic below, once numbers are in, will put in an order for the PCB.

![image](https://user-images.githubusercontent.com/75357193/161484803-c3e663b2-4186-424f-8871-d2c0e451e3ae.png)
