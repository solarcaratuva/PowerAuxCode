# Power/Aux Code
UVA Solar Car Power/Aux code repository. This repository contains the embedded code for the Power/Aux board.


## Hardware
* The PCB layouts and associated schematics for Power/Aux board can be found on the [associated repository on CADLAB.io](https://cadlab.io/project/23150).
* The board uses the [STM32G473CE MCU](https://www.mouser.com/datasheet/2/389/stm32f042c4-1851049.pdf).


## Software
* All boards run Mbed OS v6.
* Macros built into the code allow for the enabling and disabling of features (such as `printf`) as needed.


## Software Environment
* The instructions on the [UVA Solar Car Team Website](https://solarcaratuva.github.io/stm32-mbed-info) were used to help set up this project.
* The [PlatformIO Core](https://docs.platformio.org/en/latest/core/installation.html), which includes the PlatformIO CLI, must first be installed.
* The [PlatformIO IDE](https://docs.platformio.org/en/latest/integration/ide/pioide.html) can be optionally installed as either a Visual Studio Code or Atom extension.
* On Windows, the driver for the ST-Link debugger will be needed to upload programs. This driver can be found [here](https://os.mbed.com/teams/ST/wiki/ST-Link-Driver).
