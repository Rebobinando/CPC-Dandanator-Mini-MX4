# CPC Dandanator!Mini MX4

## What is this? Why?

Based on the original design from Dandare - CPC Dandanator!Mini, this design proposes the adoption/integration of MX4 connector instead of the Amstrad CPC standard 50 pin edge connector. This version then fits into the many expansion boards available up to now.

This allows for the CPC expansion boards users to enjoy this hardware, together with rest of accessories without the need of unplugging them.

Original design and complete description are available in the [Dandare Website](http://www.dandare.es/Proyectos_Dandare/CPC_Dandanator%21_Mini.html)

More development details are available in [VadeRetro forum](https://www.va-de-retro.com/foros/viewtopic.php?f=63&t=9113) 

## Features

Additionally to the features available in the original design, I added the additional following ones:

- MX4 connector format to fit into CPC expansion boards.
- CPLD is plugged into a socket for easier soldering process by hand.
- Switch for Enable/Disable the accessory instead of button.
- DIP oscillator instead of SMD one.
- Additional switch to switch on /switch off the board.

CPLD programing is fully compatible with original version available at Dandare website.

EEPROM programming original software is also fully compatible. It is available in Dandare website too.

## Bill of materials

|Qty| Component     | Value               |  Package  |
|---|---------------|---------------------|-----------|
| 3 | Capacitor     | 100nF               | SMD C0805 | 
| 2 | Capacitor     | 10uF                | SMD C0805 |
| 2 | Capacitor     | 22pF                | SMD C0805 |
| 1 | Capacitor     | 10nF                | SMD C0805 |
| 1 | IC            | CH340G              | SOP16     |
| 1 | Voltage Reg   | AMS1117-3.3         | SOT223    |
| 1 | MPF           | SST39SF040          | PLCC32    |
| 1 | CPLD          | XC9572XL            | PLCC44    |
| 1 | Oscillator    | 12 MHz              | HC49S     |
| 3 | Resistor      | 10K                 | R805      |
| 1 | USB plug      | Micro USB Type B    | SMD       |
| 1 | pin           | 1x6                 | DIP       |
| 1 | pin           | 1x2                 | DIP       |
| 2 | Button        | 6x6x9 Right Angle   | DIP       |
| 2 | Switch        | MSK-12D19           | DIP       |
| 1 | MX4 connector | DC3-50P Right Angle | DIP       |
| 1 | Socket        | PLCC32              | DIP       |
| 1 | Socket        | PLCC44              | DIP       |

## Board layout

These are the main elements:

![Elements](Pic/RWD_Dandanator_ME.PNG)

All development of this version has been performed with Eagle 8.6.0. Schematics and Board files are available, as well as Gerber files under below license agreement.

This is the board installed onto the CPC expansion board:

![BUS_Expansor](Pic/DD_MX4_Expansor_Inserted.jpg)

PCB screenshot:

![PCB_Top](Pic/DDMX4v1.2_Top_View.PNG)

![PCB_Bottom](Pic/DDMX4v1.2_Bottom_View.PNG)

## Warning & Disclaimer
If you want to build yourself, please proceed and read carefully all this information. A guide of assembly is available in VadeRetro forum [here](https://www.va-de-retro.com/foros/viewtopic.php?f=63&t=9113) . Bear in mind that all the information in this project is published in good faith and for general information purpose only. I do not make any warranties about the completeness, reliability, and accuracy of this information. Any action you take upon the information you find here, is strictly at your own risk. I will not be liable for any losses and/or damages. In case of doubts, do not hesitate to ask and I will try to help as far as I can!

## Thanks to

- Dandare and the team for carrying out the original (smart & awesome) design of this interface, for giving permission for use and modification of it, and for giving support during the development.

- All the users for VadeRetro forum, who supported the initial batch of units.

Hope we are all enjoying them!


## Redistribution

All development is Public Domain, as the original one. For latest state, please check at [Dandare website](http://www.dandare.es/Proyectos_Dandare/CPC_Dandanator%21_Mini.html)
