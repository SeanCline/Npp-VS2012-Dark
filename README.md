VS2012/2013 Dark Theme for Notepad++
=============

This is as close as I can get to a replica of the Visual Studio 2012's Dark theme in Notepad++. I created it to ease switching between files opened in Visual Studio and Notepad++. Particularly close attention has been paid to C, C++, and XML but a number of other languages have been tested.

Installation (per-machine)
--------------------------

1. Download [`VS2012-Dark.xml`](https://raw.githubusercontent.com/SeanCline/Npp-VS2012-Dark/master/VS2012-Dark.xml), making sure to get the raw version, to `%PROGRAMFILES%\Notepad++\themes` (`%PROGRAMFILES(X86)%\Notepad++\themes` on 64-bit systems).
2. Restart Notepad++.
3. Open *Settings->Style Configurator*.
4. Select `VS2012-Dark` from the theme drop-down box.
5. Click *Save & Close*

Issues
------

While the colours are very close, if not spot on, there are some differences in appearance between this theme and VS2012. Visual Studio uses information from Intelisense to differentiate between class identifiers and variable identifiers. Notepad++'s lexer is more primitive and cannot make this distinction. Notepad++ is also not as good as interpreting precompiler statements. But that's OK, you don't use them anyway, right?

If you find anything else wrong, feel free to [let me know](https://github.com/SeanCline/Npp-VS2012-Dark/issues/new).

Screenshot
----------
![Screenshot](https://github.com/SeanCline/Npp-VS2012-Dark/raw/master/screenshot.png "Screenshot")
