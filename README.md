# ranwhen – Visualize when your system was running

The repository is an extension of [this](https://github.com/p-e-w/ranwhen).

Ranwhen is a Python script that graphically shows **in your terminal** when your system was running in the past. It use logs about reboots and entry on suspend (or only about reboots if option -r have set). Have a look:

![demo](demo.png?raw=true)

Type `ranwhen.py -h` for more usage options.

# Requirements

* *nix system with [journalctl(1)](http://manpages.org/journalctl) installed
* [Python >= 3.8](http://www.python.org/); may be, programm will work on oldest version too, but I have tested only on Python 3.8
* Terminal emulator with support for Unicode and xterm's 256 color mode

The above requirements should be fulfilled by default on the majority of modern Linux distributions, where the only thing that needs to be done is usually to install Python 3.


# License

Copyright © 2013 Philipp Emanuel Weidmann (<pew@worldwidemann.com>)
(Fork by Novikov Denis Igorevich in 2021; <novikovden411@yandex.ru>)

ranwhen is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

ranwhen is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with ranwhen.  If not, see <http://www.gnu.org/licenses/>.


# Issues

If the logs is empty program crashes, but need to show an error message.
