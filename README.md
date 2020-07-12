# SenselMorphBlenderRaw
Blender Custom Modal Timer Operator for Sensel Morph's Raw Data Output

License: GPL v3

This is a boiler-plate setup for dealing with Sensel Morph's Raw data output inside of Blender. It is a rough implementation. 

This was tested on MacOS. Other operating systems may require some adjustment. There are some bugs with multiple usage inside one session of Blender. Use at your own risk. Save often.

#To Install:
1) Install/build Blender
2) Install the Sensel API library
3) Copy the included sensel directory (the sensel-lib-python directory with an __init__.py) to Blender.app/Contents/Resources/2.90/scripts/sensel
4) Make sure Sensel Morph is connected to the computer.
4) Open a terminal. CD to Blender.app/Contents/MacOS. Open Blender from the terminal.
5) Go to the scripting section.
6) Run the script. 
7) Touch Sensel Morph.
8) Notice change in colors in the viewport graphcs (data is also printed in terminal).
9) To exit, press the upper left hand corner of the Morph (as close to 0x0 as possible).
10) Confirm that Sensel Morph no longer drives viewport coloring and is not outputting data in terminal. 
11) You can re-run the script. 
* IF SENSEL MORPH IS NOT DISCONNECTED, SCRIPT WILL CAUSE HANG-UP AND BLENDER MUST BE FORCE QUIT.


---
Partially inspired by the Blendsel project https://github.com/pmauldin/HackThePlanet
