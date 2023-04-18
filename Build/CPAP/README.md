# CPAP

The wiring of the CPAP was quite challenging.

All the sources that I used are linked below.

I was able to get full control of the cpap fan from 20% to 100%.

VSR from the CPAP driver board is connected to the rock 4 GPIO pin # 37. The latest printer.cfg is available [here](README.md)

**Super 8 Pin Documentation:** 
English: https://mellow-3d.github.io/fly-super8_pins.html
Chinese (Needs translation): https://mellow.klipper.cn/#/board/fly_super8/Super8line

**PIN Diagram:**
![](../Mellow%20Fly%20Super%208%20Pin%20Diagram.png)

**VzBoT Wiring Diagram:**
https://github.com/VzBoT3D/VzBoT-Vz330/blob/master/Wiring%20Diagram/VZBOT%20330%20WIRING%20DIAGRAM%20AWD%20WITH%20CPAP.png

**Klipper documentation:** https://www.klipper3d.org/RPi_microcontroller.html?h=gpio
The documentation above shows how to find the correct pin of the rpi (rock4 in my case)
