Here's an Arduino Uno sketch that demonstrates how to create both static and moving sprites on a TFT colour display. The Arduino Uno doesn't have a great deal of memory, so  sprites are a little tricky to implement, but it can be done!

![Moving sprites on TFT display powered by Arduino Uno (Animated demo)](https://blog.nichelaboratory.com/wp-content/uploads/2022/10/Arduino-Uno-ST7735S-Moving-Sprites.gif)

The code creates a mock up display of the classic Nintendo Donkey Kong game. The display module used is an ST7735S 80x160 TFT screen sourced from eBay. I made static single-color bitmap images for the girders, ladders and oil drum, but Mario and the princess are moveable multicolor sprites.

The graphics were rendered using the Adafruit GFX library and the Adafruit ST7735 and ST7789 library.

I didn't have too many problems using the TFT display. The main issue I had was that the color codes were different to those specified in the GFX library. Check my video for information on how to resolve this issue on your own particular display module:

https://youtu.be/xCG11KJHE_Q

image2cpp: http://javl.github.io/image2cpp/

Hardware graphics captured on a Canon EOS 550D with a 60mm EF-S macro lens.

![Moving sprites on TFT display powered by Arduino Uno](https://blog.nichelaboratory.com/wp-content/uploads/2022/10/Arduino-Uno-ST7735S-Moving-Sprites-Game-Thumbnail.jpg)
