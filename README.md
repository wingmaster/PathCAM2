# PathCAM2
PathCAM2 - a 3d CAM gcode toolpath generator
This tool read STL files and creates toolpaths for a 3d CNC machine.

This is an clone of the project https://github.com/xenovacivus/PathCAM .
The origial is imperial. This clone will be metric.

The plan is to add/change the following:
- Convert to metric -> done
- Add fixed rotation buttons -> done
- Swap left and right buttons -> in progress
- Add material size and thickness -> done
- Add origin
- Add offset object to material top
- Add routing to remove all material above object
- Option to do only rough cutting
- Option to set mill type: round or square
- Lots of other things.....

I will regulary create a msi installer. Later on will find out how to do 
a svn to git commit of the source codes.

Cheers

Arnoud

# Release notes

2.0.0  1-june-2019
- Converted PathCAM to metric
- Swapped left and right mouse buttons
- changed installer uuid's
- Added tab diameter setting
- Added buttons for rotation
NOTE: gcode exports,robot and path generation untested

2.0.1  8-june-2019
- Added material settings
- Added material cube display
- Connected gcode save with speed settings
- Converted robot output to metric
NOTE: gcode exports,robot and path generation still untested
