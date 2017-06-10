Unity 5.5.1f1
Google VR Version 1.0 
Build/Tested on Android (Google Pixel. Android version 7.0)

# v5
* Aligned windows, door and globe handler. Window by the computer desk seems to be narrower then the hole in wall.
* Switched to uncompressed lightmap it had big impact on the lighting artifact.
* Removed GVR and added normal camera and then dragged GVR Viewer script to it
* Played with baked resolution, set to 4 but that generated. Unity seems to sometimes hung when I play with that parameter, e.g. when I set it to 2, i see 15/16 Compositing | 1 jobs, while unity barely uses CPU and memory and I can't hear any fans spining on GPU. After Unity restart it only took 2 seconds.
When number is low the colors looked odd, it looks like there are spots of different colors based on reflections from various objects nearby (e.g. red from sofa). There is no smooth transition.
* set all viewpoints y position to 0
* Switched shadow type to soft for area lights
* Unity showed warning that anti aliasing might significantly impact performance of mobile VR. I have disabled it.

# v6
* Changed baked resolution to advised value 80.
