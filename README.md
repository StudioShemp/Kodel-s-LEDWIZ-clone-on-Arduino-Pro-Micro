# Kodel-s-LEDWIZ-clone-on-Arduino-Pro-Micro
I take no credit for this code, it's the fantastic work of Koen from his post on https://www.vpforums.org/index.php?showtopic=51133  based on earlier work by @cyclemat

Hosting it here for re-use under permission granted on the page.

It also includes modifications to the boards.txt file by wouterrusman.

Please read the ino file commenatary carefully for instructions on locating and modifying 
- Arduino Sparkfun AVR boards definitions 'boards.txt' file
- the RawHID.h  file  from NicoHood's HIDProject.h

The project won't work without these mods.

Finally, a shout out to digitalarts for the guidance on setting up two of these in a single machine by incrementing the build.pid in the boards.txt file.
<br>
>  If you want to use more then one ledwiz clones, be sure they have different id's!<br>
>  It's the .build.pid = 0x00F0<br>
>  ;F0 is ID1, for the next ledwiz you need to set it to 0x00F1 so it's ID2.<br>
>  If you have a pinscape additionaly, this already is fixed ID8<br>

Thanks for being such an awesome community!
