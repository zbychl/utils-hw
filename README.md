# utils-hw
Hardware utilities projects

## stlink-v2-clone-to-cortex-dbg-etm-adapter
Project for simple adapter allowing to attach STLink v2 Clone to the
20-Pin Cortex Debug + ETM Connector for ARM MCUs.

### STLink v2 clone
> **WARNING**: Be careful, there is a two different STLink v2 clone pinout version: http://blog.linuxbits.io/wp-content/uploads/2016/02/P1160461_clipped.jpg

This adapter is supports the following pinout

|          |            |
|----------|------------|
| RST  - 1 | 2  - SWCLK |
| GND  - 3 | 4  - SWDIO |
| SWIM - 5 | 6  - GND   |
| 3.3V - 7 | 8  - 3.3V  |
| 5.0V - 9 | 10 - 5.0V  |




### ARM MCU JTAG
http://www2.keil.com/coresight/coresight-connectors/
