## Ender 5 Plus

The profiles I found for Prusaslicer don't cover the Ender 5 Plus.

For example, one thing we discovered is the extruder distance is not 0 on power up. You have to reset it. The g-code starts we found were actually retracting the filament while trying to put down the init line.

In Prusaslicer, File->Import->Import Config and choose Ender5Plus.ini.
