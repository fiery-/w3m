This is modified version of [w3m](http://w3m.sourceforge.net/) 0.5.3-patched from MacPorts. This version can only dump html files to plain text.

Project is created in Xcode v3.2.6 (Mac OS X 10.6). Release is i386 and works on OS X 10.5 or later (including 10.11).

```
$ w3m --help
w3m version w3m/0.5.3-OI, options lang=en,m17n
usage: cat [filename] | w3m [options]
options:
    -I charset       document charset
    -O charset       display/output charset
    -e               EUC-JP
    -s               Shift_JIS
    -j               JIS
    -T type          specify content-type
    -cols width      specify column width (used with -dump)
    -ppc count       specify the number of pixels per character (4.0...32.0)
    -dump            dump formatted page into stdout
    -S               squeeze multiple blank lines
    -help            print this usage message
    -version         print w3m version
    -endnl count     specify the number of end blank lines
```
