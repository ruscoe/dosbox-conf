# DOSBox Configuration Files

Some configuration files for [DOSBox](https://www.dosbox.com/), a DOS emulator.

Used with the Windows version of DOSBox.

Expects a directory to exist at `C:\dosbox\drives\c`.

## Links

* [DOSBox](https://www.dosbox.com/)
* [DOSBox configuration wiki page](http://www.dosbox.com/wiki/dosbox.conf)

## Usage

Copy files to DOSBox directory (see wiki link above.)

Load multiple configuration files by starting DOSBox with the `-conf` argument. Example:

`"C:\Program Files\DOSBox-0.74\DOSBox.exe" -userconf -conf dosbox-0.74-ThemePark.conf`

The `-userconf` argument will load the default configuration file (`dosbox-0.74.conf`)

Use additional configuration files to override settings in the default configuration file.
