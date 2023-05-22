# For CmBacktrace use in FreeRTOS

## Usage info

1. Change in FreeRTOS source code

    copy these files into FreeRTOS source code directory

2. Comment Hard Fault Handler in stm32f4xx_it.c & stm32f4xx_it.h

3. add _stext & _sstack to link script

    Template link script Files are given
