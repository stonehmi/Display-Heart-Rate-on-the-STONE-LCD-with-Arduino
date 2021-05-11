Some time ago, I found a heart rate sensor module MAX30100 in shopping online. This module can collect blood oxygen and heart rate data of users, which is also simple and convenient to use.

According to the data, I found that there are libraries of MAX30100 in the Arduino library files. That is to say, if I use the communication between LCD Arduino and MAX30100, I can directly call the Arduino library files without having to rewrite the driver files. This is a good thing, so I bought the module of MAX30100.

I decided to use Arduino to verify the heart rate and blood oxygen collection function of MAX30100. With STONE TFT LCD screen for monitoring blood pressure.


Note: this module by default only with 3.3 V level MCU communications, because it defaults to using IIC pin pull up the resistance of 4.7 K to 1.8 V, so there is no communication with the Arduino by default, if you want to commune with the Arduino and need two 4.7 K of the IIC pin pull-up resistor connected to the VIN pin, these contents will be introduced in the back of the chapter.

 
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
