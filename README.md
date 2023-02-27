# Black-Pill I2C Display

This is a hack and slash job of a tutorial I found on the interwebs. 
It's useful to refer to the page, but a lot of the code is there.



## STM32 Black Pill

There are two variants of the Black Pill, although I suppose when using 
the Arduino library, it all compiles the same. I'd imagine, using the lower
spec software with the higher spec device would do no damage, but writing 
code for the higer spec device, and compiling it for the lower spec one 
might result in problems. 

There are two variations of the STM32 Microcontroller that come on these boards.

The Higher Spec Model is the STM32F411CEU6.

The Lower Spec Model is the STM32F401CCU6. 

For all intensive purposes they are the same, but their pinouts and capabilities
are slightly different, as well as obviously the clock speed and amount of ram
or caches that are available. 

