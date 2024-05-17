# MacroDeck.EliteDangerousIconPack
A simple icon pack for MacroDeck for my Elite Dangerous setup for use with my [MacroDeck.EliteDangerousPlugin](https://github.com/lochkartenman/MacroDeck.EliteDangerousPlugin).

All icons have the function name in the upper part as static text. The activation status is intended to be drawn over the lower part of the icon by MacroDeck. This way the status text can be dependent on variables for instance.

All icons come in two variants with inverted colors:
1. The normal  icon has the function name in black over a transparent background while the lower status area is black.
2. The inverted variant has the function name in transparent on a black background while the lower status area is all transparent.

The effect is that you can quite freely change the color of the function name text via the background color of the button and can still chose the color of the status text freely via the font color property. 

The font used for the function names is _Arial Narrow_ hence it is advised use the same font also for the status text in MacroDeck. 

## Icon Generation
The icons have been [generated](./generate.bat) with [ImageMagick](https://imagemagick.org/) rather than drawn by hand. Hence you can easily add additional matching icons or change the font.
