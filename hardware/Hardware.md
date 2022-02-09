## Hardware

![PLL block diagram](../images/PLL_Block_diagram.png)


The hardware for this project is made up of several different PCBs.

The main PLL board is made of 5 PLL all driven form the same reference 

The boards are controlled from a custom windows application and communications between the PC and PLLS is done over RS-485

For this there are two PCBs, one connection a RS-485 transceiver to a USB to serial cable and another for connecting the ethernet cable to the PLL board

PLL boards have been designed to be stacked on top of each other. To aid in providing a single reference interface there is a reference distribution board

finally to provide a stable power source to the stacked PLLs a power distribution board has been made. 
Each board can be stacked on top of 

- [PLL Board](PLL_Board.html)
- [RS-485 Boards](RS485_Board.html)
- [Reference Board](Reference_Board.html)
- [Power Board](Power_Board.html)


[Photo of assembled PLL array](../images/PLL_Photo_04.jpg)



- [Hardware page](/hardware/Hardware.html)
- [Software page](/software/Software.html)
- [Array page](/array/Array.html)



[back](./)