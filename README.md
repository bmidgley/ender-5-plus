## Ender 5 Plus

The profiles I found for Prusaslicer don't cover the Ender 5 Plus.

For example, one thing we discovered is the extruder distance is not 0 on power up. You have to reset it. The g-code starts we found were actually retracting the filament while trying to put down the init line.

In Prusaslicer, File->Import->Import Config and choose Ender5Plus.ini.

You'll have to detach printer settings and filaments. And you also have to remove `compatible printers condition` in each detached profile. Then the Ender 5 Plus can be used with other filaments and print qualities. (If there is an easy way to export these to .ini files I can capture here, I'll add it)
