Neopixel
========

The ideas here reflect a gathering of information from these sources: 

I program the ATTiny85 chip to run a Neopixel strip with an Arduino script written by EternalCore. The idea came from an  Instructible by danasf: http://www.instructables.com/id/Use-a-1-ATTiny-to-drive-addressable-RGB-LEDs/?ALLSTEPS The previous link gives a ton of info. In connecting to the IC, make sure to remember that Digital Pin 4 is Pin 3 on the IC. 

The Adafruit programmer that danasf used didn't work for me at all. However, the Sparkfun programmer was pretty much a piece of cake (https://www.sparkfun.com/products/11801). I bought 10 of these ATTiny85 ICs ( http://www.newark.com/atmel/attiny85-20pu/ic-8bit-mcu-avr-tiny-20mhz-8-pdip/dp/68T3808?ost=68T3808 ). Amazing that I got 10 of these for under $12. I was asked about the rationale for the resistor and the capacitor. I don't know enough about electronics theory to say. I do know that mine did not work without both the resistor and capacitor, as per the instructions. 

I referred regularly to the following:

The Adafruit NeoPixel UberGuide by Phillip Burgess (http://learn.adafruit.com/adafruit-neopixel-uberguide/overview), 
The Adafruit NeoPixel Library (https://github.com/adafruit/Adafruit_NeoPixel), 

The nifty work done by EternalCore in the Adafruit forums (http://www.adafruit.com/forums/viewtopic.php?f=47&t=42204). EternalCore graciously shared his work. For EternalCore's NeoPixel code you can pick it up here (https://github.com/EternalCore/NeoPixel_Cylon_Scrolling_Eye). 

You can see some of my own code on my first GitHub. Know, though, that I will provide NO support for anything I've posted there or here. Any problems you may have with circuits, scripts, your device turning into a chocolate cupcake, is your problem, legally, morally. Most certainly, if I wrote the code, it's likely neither dependable nor well written. This information is provided by an electronic no-nothing for entertainment purposes only.  
