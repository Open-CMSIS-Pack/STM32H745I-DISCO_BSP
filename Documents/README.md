# STM32H745I-DISCO Discovery board

## Overview

The STM32H745I-DISCO Discovery kit is a complete demonstration and development platform for Arm® Cortex®-M7 and Arm® Cortex®-M4 core-based STM32H745XI microcontroller, with 2 Mbyte of flash memory and  1 Mbyte of SRAM.

The STM32H745I-DISCO Discovery kit is used as a reference design for user application development before porting to the final product, thus simplifying the application development.

The full range of hardware features available on the board helps users to enhance their application development by an evaluation of all the peripherals (such as USB OTG FS, Ethernet, USART, CAN FD, SAI audio DAC stereo with audio jack input and output, MEMS digital microphone, RGB interface LCD with capacitive touch panel, and others). ARDUINO® Uno V3, STMod+ connectors provide easy connection to extension shields or daughterboards for specific applications.

STLINK-V3E is integrated into the board, as the embedded in-circuit debugger and programmer for the STM32 MCU and USB Virtual COM port bridge.

## Getting started

- [User manual](https://www.st.com/resource/en/user_manual/um2488-discovery-kits-with-stm32h745xi-and-stm32h750xb-mcus-stmicroelectronics.pdf)

### ST-LINK driver installation and firmware upgrade (on Microsoft Windows)

1. Download the latest [ST-LINK driver](https://www.st.com/en/development-tools/stsw-link009.html).
2. Extract the archive and run `dpinst_amd64.exe`. Follow the displayed instructions.
3. Download the latest [ST-LINK firmware upgrade](https://www.st.com/en/development-tools/stsw-link007.html).
4. Extract the archive and run the `ST-LinkUpgrade.exe` program.
5. Connect the board to your PC using a USB cable and wait until the USB enumeration is completed.
6. In the **ST-Link Upgrade** program, press the **Device Connect** button.
7. When the ST-LINK driver is correctly installed, the current ST-LINK version is displayed.
8. Press the **Yes >>>>** button to start the firmware upgrade process.

## Technical reference

- [STM32H745XI microcontroller](https://www.st.com/en/microcontrollers-microprocessors/stm32h745xi.html)
- [STM32H745I-DISCO board](https://www.st.com/en/evaluation-tools/stm32h745i-disco.html)
- [User manual](https://www.st.com/resource/en/user_manual/um2488-discovery-kits-with-stm32h745xi-and-stm32h750xb-mcus-stmicroelectronics.pdf)
- [Data brief](https://www.st.com/resource/en/data_brief/stm32h745i-disco.pdf)
- [Schematic](https://www.st.com/resource/en/schematic_pack/mb1381-h745xi-b01-schematic.pdf)
