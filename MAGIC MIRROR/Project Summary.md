# Project Magic Mirror 
### Date:   DEC 2023- JAN 2024

Magic Mirror is my first product.

All the resources where very kindly provided by my Science Teacher (Dr Mcvean).


### My setup:
- 2x pi4 (2gb and 4gb ram size) 
- An external display  (touch screen)
- logitech external keyboard
- hdmi cables 
- display connectors (usually a split usb cable to usb micro )
- computer (optional)

### Plan
1. Get Magic Mirror from GitHub           
2. Check hardware compatibility 
3. Mod the Magic Mirror
 
(ALL THE BELOW WAS DONE BY DR MCVEAN )
4. Make a case and get 1 way Mirror.
5. Assembling the Mirror


With a pi 4 (2gb) and my own pi 4 I was able to quickly able to prototype
a basic Magic Mirror.
> **Image of whole setup**
>![IMAGE](assets/images/Fullview.jpg)


Moreover, I quickly learnt json editing and the Magic Mirror environment so was able to start modding.

I learnt about electron and how it was  essential for running the Magic Mirror.
I was also  found a library of 3rd party mods for the magic mirror doing many of the things I wanted to make. 
I learned how enable and use mods in Magic  Mirror. I quickly added multiple mods 
> **Image of the screen and pi setup with initial Magic Mirror**
>![IMAGE](assets/images/Screen1.jpg)
> **Image of modded magic mirror**
>![IMAGE](assets/images/c3.jpg)

Although it looks easy, making sure the pi didn't overheat or that the 
2gb ram was not a limit to performance and that it could sustain 
long periods of use proved to be a challenge which made the project stretch 
from 1 week to 3 weeks. 

To address the potential heating issues and low power usage requirements I first suggested adding a passive cooling
such as heat sinks. Additionally, since the display would be on all the time the power usage was not optimal. 
I added automated waking (on pi startup) and closing (after *t* ms delay). 
> **Image of pi autostarting the mirror and proof of its reduced memory usage**
>![IMAGE](assets/images/autostart.jpg)

This brought the project to a end and by New Year the Magic Mirror project was completed successfully.
> **Image of final product**
>![IMAGE](assets/images/processed-ABB905E0-B53C-4F99-90C0-2FCEA73494C0.jpeg)
Note: The Mirror had go through mulitple software updates. And due to me being unable to maintain the code most of the modifications had to be replaced in the end.
## USEFUL LINKS 
- https://magicmirror.builders/
- https://github.com/MagicMirrorOrg/MagicMirror/wiki/3rd-party-modules