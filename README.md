# poorDuino
Arduino-like simple development board

## Idea
Main purpose of designing `poorDuino` was to **utilize** dozen Atmega8/Atmega168 chips, which were collected by me, for few last years.

`poorDuino`'s name comes from reduced manufacturing costs (i.e. no USB programmer onboard). 

##Features
- Arduino UNO board shape,
- Connectors are fully compatible with Arduino standard,
- Two power supply: 5V and 3V3 (selected via jumper),
- Extra pull-up resitors on IIC lines (enabled by soldering jumper on bottom of the board),
- USB connector and USB2UART bridge removed,
- ICSP connector for programming (external programmer is necessary)
