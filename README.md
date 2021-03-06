# SMD Challenge Extreme Edition

I competed in the soldering competition at the Hackaday Superconference last year which aims to see how fast you can solder up the [SMD Challenge kit from makersbox](https://www.tindie.com/products/makersbox/smd-challenge/). 
Dan Maloney did a [nice little writeup](https://hackaday.com/2019/11/18/a-newbie-takes-the-smd-challenge-at-supercon/) of the event and what it entails

The normal kit starts off at 1206 components and goes down to 0201, however SMD components have been getting smaller and smaller

After finding the infamous 555 timer comes in a [8ball BGA package](https://www.ti.com/product/LMC555), I had the crazy idea to make something similar, but as small as possible

## Features
- 555 Timer in dsBGA package (1.41x1.43mm)
- 74HC4017 decade counter in DHVQFN16 (2.5x3.5mm)
- All 01005 passives (400x200um)
- 0201 LEDs (350x650um) (pretty hard to find, so might to to 0402, but that seems too big!)
- Powered from a 3V Lithium CR1220 battery
  - Should operate down to 2V at least
- Board size defined by battery (17mm circle)

## Renders

![front](/outputs/renders/front.PNG)
![back](/outputs/renders/back.PNG)
