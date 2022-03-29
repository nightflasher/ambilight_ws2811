This is the most wanted AMBILIGHT clone control software for the arduino or similar.
You just have to choose your DATAPIN for your (ws281x featured) RGB LED strip, count the LEDs of your strip and write it down to LEDCOUNT.
You can even choose a delay for SHOWDELAY ("the action to happen"), which you may try out a few times in ms - mine was 0 ms.
the BAUDRATE can be set to whatever you want to, but 115200 seems perfect for the most usecases.
And to save some power and maybe to fit better in your environment, set the desired BRIGHTNESS of the LEDs, it's in percentage and you really 
should test if you need to do the 100% or go way down to maybe 30%? 
I had no absolute dark room (like home cinema), and i wanted a bit of extra effect on this, so mine is/was 96% for 60 LEDs.

For configuration, you need to download the "Boblight Config Maker for Windows, MacOS X and Linux" from 
https://www.tweaking4all.com/hardware/arduino/boblight-config-maker/ and of course the boblight library and control software for your system from https://github.com/arvydas/boblight
