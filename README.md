# Lots of Colors

3000+ RGB colors in code ready formats for SFML (C++), Game Maker (gml), Godot (tscn) &amp; Unity (C#)

Includes hex values for all colors and names where available (Hex is also supplied code ready for SFML).

The color pool is largely taken from Pantone and the palettes are largely aimed at fixed color game development. (e.g. Commodore 64, NES).

I'd suggest using this as a reference rather than including it in full as it's unlikely you'll use 3k colors and it will add needless variables.

## Palettes Included

Sourced via: https://lospec.com/

  Color Graphics Adapter  
  Commodore 64  
  MSX / Microsoft 1983  
  Macintosh II  
  ZX Spectrum  
  Nintendo Entertainment System / NES  

Sourced via http://www.smspower.org/Development/Palette

  SG-1000
 
Pantone color names sourced via:  https://github.com/Margaret2/pantone-colors
Pantone PMS (Pantone Matching System) colors sourced via: http://www.excaliburcreations.com/pantone.html

Pantone colors names are copyright Pantone.

## Code Examples

SFML rgb:			static const sf::Color cga_02(245,85,85); // FF555555  
SFML hex:     static const sf::Color cga_02(0x00555555); // (245,85,85)  
Game Maker:   col_cga_02 = make_color_rgb(245,85,85);  
Unity:        public Color cga_02 = Color(0.961F, 0.333F, 0.333F);  
Godot:        var col_cga_02 Color(0.961, 0.333, 0.333)  

## Notes

Hex values notes i.e. // FF555555 are available in the included excel file.

For 0-1 RGB rounding was done using the excel function round(), which rounds to the nearest integer, if you are using a language that always rounds down this may cause slight variations. 
