dewi-arduino
=============

Code to run on dewi's arduino.

Uses HMC6343 compass through compass.h

Installing
----------

```bash
$ git clone https://github.com/abersailbot/dewi-arduino.git
$ cd dewi-arduino
$ git submodule init
$ git submodule update
```

Now, if ino tool is installed correctly (if you're using
[kitty-provisioner](https://github.com/abersailbot/kitty-provisioner) this is
done for you), you can compile with:

```bash
$ ino build
$ ino upload
```

Alternately, use make for all the previous steps:

```bash
$ make install
```

Licence
-------

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program.  If not, see <http://www.gnu.org/licenses/>.
