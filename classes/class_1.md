###Class: Light

Attributes:

on (boolean)

numberOfLights (integer)

color (string)

brightness (float, 0 to 1)

lightbulbsPerLight (integer)

lightbulbStatus (boolean: on/off = working/broken)


Methods:

changeOnStatus (change light to on or off)

changeColor (change color attribute)

changeBrightness (dim or brighten lights)

calculateNeededLightbulbs (numberOfLights * lightbulbsPerLight - all lightbulbs

with lightbulbStatus "broken")
