# poorDuino
Arduino-like simple development board

## Idea
Main purpose of designing `poorDuino` was to *utilize* dozen Atmega8/Atmega168 chips, which were collected by me, for last few years. I do like Arduino as a form factor and don't like as IDE. Thus I decided to design this board to fulfil my not so sophisticated expectations: keep compatibility with original Arduino Uno and no support for programming via USB (ISP FTW!).

`poorDuino`'s name comes from reduced manufacturing costs (i.e. no USB programmer onboard). It might be decreased more, but it would not fulfill my needs.

##Features
* Arduino UNO board shape,
* Connectors are fully compatible with Arduino standard,
* Two power supply: 5V and 3V3 (selected via jumper),
* Extra pull-up resitors on IIC lines (enabled by soldering jumper on bottom of the board),
* USB connector and USB2UART bridge removed,
* ICSP connector for programming (external programmer is necessary)

## Resources
1. Arduino UNO https://www.arduino.cc/en/Main/arduinoBoardUno
