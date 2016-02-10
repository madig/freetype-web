---
layout: page
title: Links
---

The links collected in this section are useful if you want to put FreeType into a larger frame of understanding.

## Reference Sites

* [Microsoft Typography][ms]: Microsoft's OpenType specification and developing tools
* [Apple Fonts][apple]: Apple's TrueType specification and other things
* [Adobe Typography][adobe]: PostScript fonts specifications and developing tools

Detailed information on the font formats supported by FreeType can be found in the file [formats.txt][formats], which is part of the FreeType source code bundle.

[ms]: http://www.microsoft.com/typography/
[apple]: http://developer.apple.com/fonts/
[adobe]: http://www.adobe.com/products/type.html
[formats]: http://git.savannah.gnu.org/cgit/freetype/freetype2.git/tree/docs/formats.txt

## Font Tools

* [TTX][ttx]: an OpenType assembler and disassembler
* [FontForge][fontforge]: a free, powerful graphical font editor, including a TrueType instructions debugger (using FreeType)
* [TrueTypeViewer][ttv]: a free, powerful OpenType viewing tool with a TrueType instructions debugger (not using FreeType)
* [ttfautohint][ttfautohint]; a tool to auto-hint TrueType fonts, based on FreeType's auto-hinting engine (still under development)

[ttx]: https://github.com/behdad/fonttools/
[fontforge]: http://fontforge.org/
[ttv]: http://home.kabelfoon.nl/~slam/fonts/truetypeviewer.html
[ttfautohint]: http://www.freetype.org/ttfautohint/

## Font Shaping and Layout Engines

These libraries work on top of font rendering libraries like FreeType to provide sophisticated text (string) layout, being able to handle OpenType features in particular. All of them use Unicode for font and text encoding.

* [Pango][pango]: the layout library used by Gnome's GTK+ framework
* [ICU][icu]: a layout library originally developed by IBM, used for example in XeTeX, an internationalized successor of TeX
* [HarfBuzz][harfbuzz]: a text shaping library (still under heavy development), originally based on FreeType 1's OpenType layout support

[pango]: http://www.pango.org/
[icu]: http://www.icu-project.org/
[harfbuzz]: http://harfbuzz.org/

## Other Font-related Libraries

* [T1Lib][t1lib]: a Type 1 fonts library (no longer under development)
* [VFLib][vflib]: a library especially for accessing TeX fonts (no longer under development)

[t1lib]: http://www.t1lib.org/
[vflib]: http://www-masu.ist.osaka-u.ac.jp/~kakugawa/VFlib/
