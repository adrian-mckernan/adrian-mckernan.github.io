## Hardware

![PLL block diagram](../images/PLL_Block_diagram.png)

Each PCB contains 5 LTC6946 PLLS. Each PLL shares the same 10MHz source.

In order to be able to adjust the output phase of each PLL the square wave 10MHz reference is put through a low pass filter with a Varactor. By changing the voltage on the varactor the rise time of the square wave is adjusted moving the point at which the PLL locks on to the reference. This voltage is output form a DAC on the STM32F051 microcontroller




<img src="../images/PLL_top_anotated.png" alt="PLL Board" width="500"/>



| Reference | description |
| -------| ------|
|1 | 10 MHz reference  input|
| 2 | Hex invertor reference  buffer |
| 3 | Power input |
| 4 | RS-485 Interface |
| 5 | RS-485 transceiver | 
| 6 | Microcontroller| 
| 7 |  PLL 
| 8 | Attenuator | 

![PLL block diagram](../images/PLL_Photo_05.jpg)


A pdf of the schematic for the main board can be found [Hardware]() 

[back](./)