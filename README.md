# Rainbow-Space-Invader-Prints

With the OpenScad sketch provided, you can print rainbow colored objects/space Invaders. To do so, the sketch will slice your object into levels, which you can print level by level with a different color. It will also provide structure, wich will the printer allow to stack and align the levels perfectly.

Instructions:

1. load your obejct into the sketch (look into the sketch for more informations)
2. set your print level in the header of the sketch (e.g. 0.5 & 0 , this will create a level from 0 to 0.5)
3. render your object with "F6" and export it as .stl
4. load your .stl into your slicer/g-code creator. Use following settings
        -- Infill: 50%
        -- z-axis lift: 3 mm (this will lift the z-axis during moves, to prevent the printer from crashing. It has to be at least as high as the print is)
5. Export the G-Code and print it with your favorite color
6. when the level is finished remove the skirt and the support blocks in the corners but leave the object itself
7. repeat from step 2 with new levels (now following 1 & 0.5 , this will the printer affect to build ontop of the first     level)

Notes: With the settings above the printer should not crash into the levels printed before.
       The 4 blocks in the corners are there to help align the object (they kind of "mark" the outline of the print)
       
Images:

<a target="_blank"><img src="http://postimg.org/image/xwnqj1ue3/" border="0"></a>

<a target="_blank"><img src="https://photos-6.dropbox.com/t/2/AAAySxBiyuQyGWgMCqpb_objgBQlFv9Xm07NjdgM0AA5Ng/12/87296860/jpeg/32x32/3/_/1/2/IMG_20150403_223710-Edit.jpg/CNyW0CkgASACIAMoASgCKAM/JEXg_pTyVOwQPxf1AheL07w-5Wr7nIKYNbUYtICrbmo?size=1024x768" border="0"></a>

<a target="_blank"><img src="https://photos-3.dropbox.com/t/2/AADvX_lK2Cr3WX8J0hqVpn-1rMBmiy6zucUTr48zABtHhQ/12/87296860/jpeg/32x32/3/_/1/2/IMG_20150403_223758-Edit.jpg/CNyW0CkgASACIAMoASgCKAM/izZH9VJ8SbTkexbEjTKsE-rdBHuYIg5ew-HC4Gi8eWY?size=1024x768" border="0"></a>

<a target="_blank"><img src="https://photos-6.dropbox.com/t/2/AADZikyKM01H-AwhFEfaUFvxbSAqRhVxze90LcOxZ4z5Gg/12/87296860/jpeg/32x32/3/_/1/2/IMG_20150403_223744-Edit.jpg/CNyW0CkgASACIAMoASgCKAM/ttlSrPxzOoLKvwlLG0BzpEaYBZrAAiBWzT0SgpkD5IQ?size=1024x768" border="0"></a>
