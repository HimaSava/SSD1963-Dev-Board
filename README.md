# SSD1963-Dev-Board

SSD1963 is a cheap LCD display chip. It is easy to use and it is preety cheap when compared to the others out there.
Unluckyly being cheap comes with it's flaws. The chip comes in a 128 pin QFP and is hard for beginners to solder without the right tools. But the biggest issue is PCB layout. Unless you are cutting corners on decaps the chip needs 40 seperate D-Caps.
And the worst part there is no guidelines of a dev board with any kind of layout out there to help the beginners.
Well through multiple revisions and sheer luck I designed the whole dev board and had it manufactured and tested.
To my surprise it works with out any hitchs. So I am sharing the files here. 

## Now some specs on the actual Dev Board:
It has the SSD1963 chip and also has the TSC2046 Touch Sensor chip.

The dev board was designed with a particular display(resistive touch) in mind and I have attached the datasheet for it. Based on your display you may need to change the LCD connector.

In interfacing the SSD1963 is used in 8080 mode(Check datasheet) and the touch sensor uses SPI protocol. For now I have added a FRC connector with all the pins that are needed to drive the board, if you want to change it be my guest.

Right now I am still making modifications to the board, so expect some changes in the future and also ping me if you have any suggestions.
