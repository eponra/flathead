# flathead
The first tower-slinger there was.
Became a reality because i wanted to put the cantilever idea to the extreme, and proving that this can work.
Testbed for a lot of ideas, but with that also a very reliable printer, which now
printed roughly 1500h without bigger problems.
And because this gave me so much joy, the reason flatpack (the foldable tower-slinger) even became a thing.


https://user-images.githubusercontent.com/66600478/187232003-ea716ff7-21ce-4158-b240-b177a1a8f67b.mp4
Also has the most satisfying homing sequence like ever.

https://user-images.githubusercontent.com/66600478/187231722-0c1ebc80-13b8-49a5-a3d9-7ca5fb9cb5c2.mp4

https://user-images.githubusercontent.com/66600478/183500945-2cf039b2-9133-45dd-af40-6a08152f20f8.mp4
(flatpack and flathead printing gridfinity parts; flatpack with the old hotendsetup (4010 hotend, 3010 for partcooling)


###### Technical Data:

- fixed bed cantilever, with an "extruder on a pole"-setup
- buildvolume of 200x200x140 (so kinda "flat")
- heated bed that can reach up to 110°C
- Hotend capable of temperatures up to 300°C, if you choose the Copper NF Smart 500°C
- runs RRF with Mellows wonderful Fly RRF-E3, which is sadly discontinued


###### Firmware:

- RRF configuration is available at [firmware/rrf](firmware/rrf). Tested with the Mellow Fly RRF-E3


###### Some words of caution:

- As you can imagine, a fixed bed cantilever is not optimal for fast speeds or
  larger printvolumes.
- Thankfully, we dont have to deal with a large printvolume. Speed and Acceleration are however a concern here.
Rapid changes in direction can be challenging for any motion system and even more so with this motion system.
As a result consider setting your print speeds and accelerations conservatively.
- So why the fixed bed cantilever? Because it simply looks cool.
- Dual rails are used for load distribution on both the Y and Z axis; these can be a bit
  tricky to align, and can and will cost you a few grey hairs.
- last word of caution: I encourage you to take your time building flathead, and make certain everything is square, and all the motion system moves smoothly, while everything that should not move is rigid and secure without much play or flexing. 
- its a (functioning) testbed printer, and will continue to undergo active development and improvements. That said, its a pretty solid design.
- the heatbed mounts is the only thing that may need some work. Here i went with a 4-point-bed, and "converted" it to a 3-point by adding an adapter. You should rather go with a proper 3-point bed and cut the back bedmount a bit shorter, OR cut that adapter out of aluminium

## This is free for everyone to download and build, or of course to just look at it and take some inspiration or ideas from it. :)

###### ToDo-List
- flathead uses an old heatbed i had lying around, which was 4-point-leveling only, which i adapted to 3-point with an adapter i 3D printed out of PET.
This is suboptimal, as you have quite the flex on the back part of the bed. I want to change that out some day, and then cut that back mount back in size.


## Design files

[Fusion 360](https://a360.co/3vLUHdm)

This link is sadly viewable only, as I am using the free version of Autodesk
Fusion 360.

The link to the latest stable F360 file (Ver2) is [here](https://drive.google.com/file/d/1PPvhmMehtANg5mRPMscpXjDGD7wADqRG/view).

The link to the latest stable .step file (Ver2) is [here](https://drive.google.com/file/d/1e0E6sqXQLTobU6fHGJwHO7pLPgfEzkLe/view?usp).

###### Changelog:
- from V1 to V2 there were a few changes to the spoolholder.


###### A few words of gratitude:

The initial idea of a fixed bed cantilever was not mine, but came from
[apsu](https://github.com/apsu), a constant resident of the
#reprap-and-custombuilds channel in the [3D Printing
discord](https://discord.gg/pQRvDQHk67).  With this i built flathead, the
bigger brother of flatpack, and without [apsu](https://github.com/apsu/) none
of this would have happened.

Also, special thanks to [oliof](https://github.com/oliof/), another extremely
helpful member and Mod of 3D printing, and also a walking dictionary on obscure
3D printing and mechanical knowledge.  And of course, a thank you to everyone
else i forgot from 3D printing and especially the #reprap-and-custombuilds
channel.

Also, everyone nagging me multiple times a day in the super secret
#wheres-flatpack channel...


Flathead is licensed under [GPL v3.0](/LICENSE).

