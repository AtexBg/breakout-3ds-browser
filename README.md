# Breakout from 3DS Web Browser

For thoses who don't know, on the 3DS web browser if you click on "*Most visited favourites*" multiple times it loads a little JavaScript game or Breakout.

### And by exploring the RomFS of 3DS system apps (including the web browser) i found the file **romfs:/browser/page/e.js**, that was the breakout game!

But it was using internal APIs from the 3DS (mostly *navigator.webkitGetGamepads()*) so i had to rewrite the input handler, so you can play it with the keyboard

You can test the game with [my online ported version](https://atexbg.github.io/breakout-3ds-browser)
