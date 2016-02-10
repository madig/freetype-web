---
layout: page
title: Downloads
---

## Stable Releases

Stable releases of the FreeType packages, including source code, documentation, demo programs, and support tools can be downloaded directly from

* <http://savannah.nongnu.org/download/freetype/>
* or from <http://sourceforge.net/projects/freetype/files/>

Both sites have mirrors worldwide.

Windows binaries of FreeType can also be downloaded directly from this [download page][ftwin] (version 2.3.5) of the [GnuWin32][gnuwin32] project, or from [GTK's download page][ftgtk] (version 2.4.2).

The latest Freetype 1 release, today mainly of historical interest only, can be downloaded [here][ft1].

[ftwin]: http://gnuwin32.sourceforge.net/packages/freetype.htm
[gnuwin32]: http://gnuwin32.sourceforge.net/
[ftgtk]: http://www.gtk.org/download/win32.php
[ft1]: http://sourceforge.net/projects/gnuwin32/files/freetype/1.4/

## Development Versions

Using Savannah's [cgit] interface you can download snapshots created on the fly for any commit entry.

Downloading and compiling a development snapshot is one of the first things to do when you encounter something that looks like a bug in FreeType. Note that we do not guarantee that all development snapshots work on a given day, though this should be the normal case.

[cgit]: http://git.savannah.gnu.org/cgit/freetype/

## Support Tools and Binaries

### GNU Make for Win32

[GNU Make] is required to use the FreeType build system from a command line prompt.

Note that the binary comes from the excellent [MinGW distribution], which we highly recommend over Cygwin, if you don't need POSIX-compliance, in terms of ease of use and performance.

After installation you should check that it is correctly invoked by typing:

    make -v

The first lines should read:

    GNU Make 3.81
    Copyright (C) 2006  Free Software Foundation, Inc.
    This is free software; see the source for copying conditions.
    There is NO warranty; not even for MERCHANTABILITY or FITNESS FOR A
    PARTICULAR PURPOSE.

Newer version work also, of course.

[GNU Make]: http://sourceforge.net/projects/mingw/files/MinGW/Extension/make/
[MinGW distribution]: http://www.mingw.org/

### Project Files

The FreeType source code bundle contains project files for various versions of Microsoft Visual C++ and Visual Studio for x64, Windows 32, and Windows CE. However, these files have been contributed and might be out of date, thus use them with care.

For classic MacOS, support files for MPW and CodeWarrior are provided.

### FreeType Jam for Win32 and GNU/Linux

Since release 2.0.2, FreeType and its demo programs can be compiled with an alternative build tool called ‘jam’. Jam is a small, portable, and open-source replacement for ‘make’ that is a lot easier to use, and which transparently supports multiple platforms and compilers.

Binaries are available from the [download page on SourceForge](http://sourceforge.net/project/showfiles.php?group_id=3157).

[This page](http://freetype.org/jam/index.html) gives more information regarding Jam and FreeType.

**Due to lack of resources, there is no Jam support currently for FreeType. Volunteers are highly welcomed**.
