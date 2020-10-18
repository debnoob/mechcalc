# mechcalc

Mechanical Engineering Calculators, Chuck McKyes
v1.2.2 October 2020

Copyright (C) 2020 Chuck McKyes

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.



*** Verify calculations produced by this software. ***

All calculations are approximate estimates. Actual specifications
are available from equipment manufacturers.

Pump power and head assume cold water being pumped.
Vapour pressure of a mixture uses Raoult's law.

This python script can be run using "python3 -m mechcalc" on the
command line or by creating a shortcut.

In Debian, a desktop shortcut can be created by creating
a file with a .desktop extension (e.g., "MechCalc.desktop").
Make the contents this:

[Desktop Entry]
Version=1.1.2
Type=Application
Name=MechCalc
Comment=
Exec=python3 -m mechcalc
Icon=
Path=
Terminal=false
StartupNotify=false

In Windows, right-click anywhere and create a shortcut.
Right click again and select Properties.
Enter "<your python install directory>\pythonw.exe -m mechcalc"
in the "Target:" field, and <your python install directory>
in the "Start in:" field.

"pythonw.exe" starts the script without a command line console.
