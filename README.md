# i2cLCD1602

makecode I2C LCD1602 package for micro:bit  

Author: shaoziyang  
Date:   2018.Mar  


  


## usage

open your microbit makecode project, in Add Package, paste  



to search box then search.

## I2C Address  
- PCF8574: 39  
- PCF8574A: 63  

## API

- TestFunc()  
Test the add Function is work.  

- LcdInit(Addr: number)  
Initial LCD  
Addr: I2C Address.  

- ShowNumber(n: number, x: number, y: number)  
show a number in LCD at given position.  
n: number will be show  
x: is LCD column position, [0 - 15]  
y: is LCD row position, [0 - 1]  

- ShowString(s: string, x: number, y: number)  
show a string in LCD at given position.  
s: string will be show  
x: is LCD column position, [0 - 15]  
y: is LCD row position, [0 - 1]  

- on()  
turn on LCD  

- off()  
turn off LCD  

- clear()  
clear LCD content  

- BacklightOn()  
turn on LCD backlight  

- BacklightOff()  
turn off LCD backlight  

- shl()
shift left screen

- shr()
shift right screen


## Demo



## License

MIT

Copyright (c) 2018, microbit/micropython Chinese community  

## Supported targets

* for PXT/microbit


