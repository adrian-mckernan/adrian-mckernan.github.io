## Hardware

![PLL block diagram](images/PLL_Block_diagram.png)

Each PCB contains 5 LTC6946 PLLS. Each PLL shares the same 10MHz source.

In order to be able to adjust the output phase of each PLL the square wave 10MHz reference is put through a low pass filter with a Varactor. By changing the voluatge on the varactor the rise time of the square wave is adjusted moving the point at which the PLL locks on to the reference. This voltage is output form a DAC on the STM32F051 micrcontroller

A pdf of the schematic for the main board can be found [Hardware]() 

[back](./)