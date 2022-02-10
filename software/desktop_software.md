## software
![Desktop Software](../images/software_general.png)

The aim of the desktop software is to be able to make changes to either a single board, a group of boards aor all boards at tehs ame time.

The general tab allows the frequency off all boards to be controlled.

If you want to change the frequency of an individual board then use the local tick box.

Add PLL to your selected boards for changing phase or adjusting phase  and power by using the tick boxes under program.

The phase and power are separated form programming as they don't communicate with the PLL but change the DAC voltage on the phase shifter and the attenuator level.

pressing mute will automatically end a packet to the PLL to mute the output.

![Desktop Software](../images/software_registers.png)

A finer control over induvial register setting with in the PLL is available in the register tab.

After setting a single register these setting can be copied to other PLLs. Once you have configured your registers in the software these values have to be sent to the PLL by programming them from the general tab.#

[Desktop software Repository](https://github.com/adrian-mckernan/Software/tree/main/LTC6946)