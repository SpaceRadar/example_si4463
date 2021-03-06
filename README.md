# Repo of project **example_si4463**

Examples for [si4463 driver](https://github.com/Lab409/driver_si4463)

## Who designed this

Designed by [Lab409](http://lab409.ru):

* *Danil Borchevkin*

* *Alex Saveliev*

* *Natalia Bannikova*

## Licence

See ***LICENCE*** file.

## What included

* ***/docs/*** - driver for si4463:

    * ***../docs/Si4463 project pinout.xlsx*** - Excel file with convinient pinout

    * ***../docs/si4463_spi.dwf3work*** - settings file for Digilent WaveForms (signal analyzer)

* ***/stm32_si4463_sw4stm32/*** - demo-project for STM32F10x and Si4463 in SW4STM32 IDE (gcc toolchain) where:

    * ***../stm32_si4463.ioc*** - project for STM32CubeMx 4.21

    * ***../Drivers/si4463/Inc/si4463.h*** - header of the si4463 driver

    * ***../Drivers/si4463/Src/si4463.c*** - source of the si4463 driver

    ***../Drivers/si4463/Inc/radio_config_Si4463.h*** - config header generated by [WDS](http://www.silabs.com/products/development-tools/software/wireless-development-suite)

* ***/stm32_si4463_make/*** - demo-project for no IDE gcc toolchain (with makefile) where:

    * ***../stm32_si4463.ioc*** - project for STM32CubeMx 4.21

    * ***../Drivers/si4463/Inc/si4463.h*** - header of the si4463 driver

    * ***../Drivers/si4463/Src/si4463.c*** - source of the si4463 driver

    ***../Drivers/si4463/Inc/radio_config_Si4463.h*** - config header generated by [WDS](http://www.silabs.com/products/development-tools/software/wireless-development-suite)

* ***/nucleo_f103rb_si4463_sw4stm32/*** - demo-project for Nucleo F103 where:

    * ***../stm32_si4463.ioc*** - project for STM32CubeMx 4.21

    * ***../Drivers/si4463/Inc/si4463.h*** - header of the si4463 driver

    * ***../Drivers/si4463/Src/si4463.c*** - source of the si4463 driver

    ***../Drivers/si4463/Inc/radio_config_Si4463.h*** - config header generated by [WDS](http://www.silabs.com/products/development-tools/software/wireless-development-suite)

* ***Batch_Si4463.txt*** - [WDS](http://www.silabs.com/products/development-tools/software/wireless-development-suite) batch file for demo project

* ***si4463_revb1_empty_framework.xml*** - [WDS](http://www.silabs.com/products/development-tools/software/wireless-development-suite) config file for the demo project.

* ***README.md*** - this file

* ***LICENCE*** - file with licence

## Errata

Please see [wiki of the project](https://github.com/Lab409/driver_si4463/wiki).

## Additional info

Please see [wiki of the project](https://github.com/Lab409/driver_si4463/wiki).

## Feedback

Tech questions: danil.borchevkin@lab409.ru

Other questions: danil.borchevkin@lab409.ru