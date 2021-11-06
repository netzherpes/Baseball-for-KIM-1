# Baseball-for-KIM-1
I've discovered that Robert 'Bob' Leedom published another game called Baseball in the KIM user notes issue 16: enter image description here

Sadly the "listing" of the game was pure HEX, no source file. Typing in these listings is straight forward, but sadly the scan of the article is, well, miserable and to distinguish between 8 and B is sometimes impossible. So, as long as we have no additional informations, this game can not be reconstructed.

Some infos about the game: It fits in an unexpanded KIM-1, and is being played with the keypad and the LEDs

enter image description here

You can find the whole article here on Hans' site http://retro.hansotten.nl/uploads/files/6502%20user%20notes%2016.pdf

Let's see what will happen

Update 06.11.2021

I've found a slight better copy of the KIM User Notes and checked every byte of my typed in HEX file. Five Bugs later I have something up and running. PAPERTAPE FILES

I've played the 'batting training' and yould not find any errors. For the 2 player version of the game you need to change address $002C to >0 :D
