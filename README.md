# Baseball-for-KIM-1
I've discovered that Robert *'Bob'* Leedom published another game called Baseball in the KIM user notes issue 16:
![enter image description here][1]

The "listing" of the game was pure HEX, no source file given.
Typing in these listings is straight forward, but sadly the scan of the article is, well, miserable and to distinguish between 8 and B is sometimes impossible.
So, as long as we have no additional informations, this game can not be reconstructed. 

Some infos about the game: 
It fits in an unexpanded KIM-1, and is being played with the keypad and the LEDs

You can find the whole article here on Hans' site [http://retro.hansotten.nl/uploads/files/6502%20user%20notes%2016.pdf][2]

I've found a slight better copy of the KIM User Notes and checked every byte of my typed in HEX file. Five Bugs later I have something up and running.

## How to play

There are two game modes: 

 - A one player batting pactice mode (default) 
 - A two player mode where one throws the ball (with the buttons 0-5) and one player has to hit;  change the game mode by setting $002C to 1

![enter image description here][3]

The pitcher (in one player mode the computer) decides how the ball is thrown. The baseball then flies immediately to the Batter.
| Key | Pitch |
|--|--|
| 0 | slow Ball |
| 1 | fast Ball |
| 2 | up curve |
| 3 | down curve |
| 4 | riser |
| 5 | sinker |

![enter image description here][4]

The Batter has to time very carefully when to hit with the button **B**

![enter image description here][5]

I've played the 'batting training'  and yould not find any errors. 

There is the chance to add external switch to give you a better game experience. You can set the pitch on a multi position switch and include two buttons to throw and hit. (I need to try this soon)


## Special thanks to: 
**Bob Leedom**, who dug in his basement in the search for all the missing documents, scanning and sending it 
*You're the best!*
**Hans Otten** for his preservation of all the documents online,
**Liu** for building the PAL-1 (an affordable and full KIM-1 clone)


  [1]: https://github.com/netzherpes/Baseball-for-KIM-1/blob/main/KIM1_BB_small.png
  [2]: https://github.com/netzherpes/Baseball-for-KIM-1/blob/main/KUN_16_Baseball.pdf
  [3]: https://netzherpes.de:443/content/images/20211103095701-bb_ins.png
  [4]: https://netzherpes.de:443/content/images/20211107100406-bb_ball_fly.png
  [5]: https://netzherpes.de:443/content/images/20211107111554-bb_ball_hit.png

