# WeActStudio.STM32F103RCxx

We use the latest STM32F103RCT6 chip design development board; STM32F103RCT6 has a 72Mhz main frequency, 256k flash, and 48k sram.



V1.0 Pins labeled incorrectly ：

In document [STM32F103RCxx__V1.0_Sch.pdf](https://github.com/WeActStudio/WeActStudio.STM32F103RCxx/blob/main/Hardware/STM32F103RCxx_Sch_V1.0.pdf), the H1 header shown at the bottom left of the schematic labels pins 25, 27 and 29 as 3V3. The board layout picture on the right hand side labels pins 25, 27 and 29 as 5V. Either the schematic or the layout is incorrect. There are similar problems with pins 26, 28 and 30 which are labeled VBUS in the schematic and 3.3 in the layout.
