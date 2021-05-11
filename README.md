Before starting this project, I thought about some simple features:

•  Heart rate data and blood oxygen data were collected

•  Heart rate and blood oxygen data are displayed through an LCD screen

 

These are the only two features, but if we want to implement it, we need to do more thinking:

•  What master MCU is used?

•  What kind of LCD display?

 

As we mentioned earlier, we use Arduino for the MCU, but this is an LCD Arduino project, so we need to choose the appropriate LCD display module. I plan to use the LCD display screen with a serial port. I have a STONE STVI070WT-01 displayer here, but if Arduino needs to communicate with it, MAX3232 is needed to do the level conversion.

 

Then the basic electronic materials are determined as follows:

1. Arduino Mini Pro development board

2. MAX30100 heart rate and blood oxygen sensor module

3. STONE STVI070WT-01 LCD serial port display module

4. MAX3232 module

 https://www.stoneitech.com/news/sharing/arduino-lcd-display-project.html
