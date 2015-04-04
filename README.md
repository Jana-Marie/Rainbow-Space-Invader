# Rainbow-Space-Invader


With the OpenScad sketch provided, you can print multi/rainbow colored objects/space Invaders. To do so, the sketch will slice your object into levels, which you can print level by level with a different color. It will also provide structure, wich will the printer allow to stack and align the levels perfectly.

Instructions:

1. load your obejct into the sketch (look into the sketch for more informations)
2. set your print level in the header of the sketch (e.g. 0.5 & 0 , this will create a level from 0 to 0.5)
3. render your object with "F6" and export it as .stl
4. load your .stl into your slicer/g-code creator. Use following settings

        -- Infill: 50%
        -- z-axis lift: 3 mm (this will lift the z-axis during moves, to prevent the printer from crashing. It has to                               be at least as high as the print is)
        
5. Export the G-Code and print it with your favorite color
6. when the level is finished remove the skirt and the support blocks in the corners but leave the object itself
7. repeat from step 2 with new levels (now following 1 & 0.5 , this will the printer affect to build ontop of the first     level)

Notes: With the settings above the printer should not crash into the levels printed before.
       The 4 blocks in the corners are there to help align the object (they kind of "mark" the outline of the print).
       also they all have to have the same distance to the center of the print, take care of that, if you have to            move them.
       
Tested with the Space-Invader by User_4574 http://www.thingiverse.com/thing:35870
       
To-do: Improving the spacing and positioning system
       
Images:

![image](http://s17.postimg.org/nmlbjt4in/IMG_20150403_223729_Edit.jpg)
![image](http://s27.postimg.org/9cd8bf6nn/IMG_20150403_223710_Edit.jpg)
![image](http://s27.postimg.org/r2jia79mb/IMG_20150403_223758_Edit.jpg)
![image](http://s22.postimg.org/svs8o84ch/IMG_20150403_223744_Edit.jpg)

Yea, missing orange and magenta for a rainbow ;-;
