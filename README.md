LOLduino
========

Currently Arduino IDE is used to program ATmega168, ATmega328, ATmega1280, ATmega2560, Atmega32u4. But other AVRs such as ATmega324, ATmega644, whose support is not provided by Arduino Community, can also be programmed using Arduino IDE. I have hacked the the IDE a little bit so that these controllers can be programmed too.Advantages withthese controllers is that you have bit more of gpio pins left even after the  arduino footprint and you can attach some more peripherals to it.

To use the the support for it you need to copy the folder LOLduino in ${arduino_directory}-> hardware, then restart the IDE. You will get a LOLduino option under Tools->Boards...
Cheers!!
 