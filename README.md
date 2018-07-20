LOLduino
========

Currently Arduino IDE is used to program ATmega168, ATmega328, ATmega1280, ATmega2560, Atmega32u4. But other AVRs such as ATmega324, ATmega644, whose support is not provided by Arduino Community, can also be programmed using Arduino IDE. Tweaked the IDE a little bit so that these controllers can be programmed too. Advantages with these controllers is that they have bit more of gpio pins as required for arduino footprint so, more peripherals can be attached to these extra gpio pins. And these added peripherals can be programmed using existing Arduino libraries. 

To use the support for it you need to copy the folder LOLduino in ${arduino_directory}-> hardware, then restart the IDE. You will get a LOLduino option under Tools->Boards...
Cheers!!
 
